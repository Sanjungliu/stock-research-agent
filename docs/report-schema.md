{
  "ticker": "AAPL",
  "recommendation": "BUY",
  "confidence": 81.2,
  ""investment_thesis"": "",
  "strengths": [
    "Revenue increased 12% year-over-year",
    "Strong cash reserves of $80 billion",
    "Growing services business with recurring revenue",
    "Strong brand recognition and customer loyalty"
  ],
  "risks": [
    "Heavy dependence on iPhone sales",
    "Increasing competition in AI products",
    "Potential regulatory scrutiny in Europe",
    "Supply chain concentration in specific regions"
  ],
  "supporting_evidence": [
    {
      "type": "financial",
      "evidence": "Revenue increased 12% YoY",
      "source": {
        "title": "Apple Q2 2026 Earnings Report",
        "url": "https://...",
      }
    },
    {
      "type": "news",
      "evidence": "Company announced new AI-powered products",
      "source": {
        "title": "Apple unveils next-generation AI platform",
        "url": "https://...",
      }
    }
  ]
}

ticker
- description: targeted stock that are going to be analyzed
- value: free text, eg. BBCA, AAPL
- required: true

recommendation
- description: recommendation from the agent is it to buy or sell the stock of ticker
- value: BUY, SELL, HOLD
- required: true

confidence
- description: confidence rate of the recommendation resulted by the agent
- value: float, eg. 89.2
- required: true

"investment_thesis"
- description: summary of the analysis resulted by the agent
- value: free text
- required: true

strengths
- description: positive characteristics of the company that support the investment thesis.
- value: array of strings. eg. [
  "Revenue increased 12% year-over-year",
  "Strong cash reserves of $80 billion",
  "Growing services business with recurring revenue",
  "Strong brand recognition and customer loyalty"
]
- required: true

risks
- description: reasons the recommendation could be wrong
- value: array of strings. eg. [
  "Heavy dependence on iPhone sales",
  "Increasing competition in AI products",
  "Potential regulatory scrutiny in Europe",
  "Supply chain concentration in specific regions"
]
- required: true

supporting_evidence
- description: specific facts, metrics, news, or observations used to reach the recommendation.
- value: array of objects. eg. [
  {
    "type": "financial",
    "evidence": "Revenue increased 12% YoY",
    "source": {
        "title": "Apple Q2 2026 Earnings Report",
        "url": "https://...",
        "published_at": "2026-04-28"
    }
  }
]
- required: true
