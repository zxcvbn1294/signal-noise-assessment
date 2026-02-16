# Signal-Noise Assessment Framework

<p align="center">
  <strong>資訊品質辨識框架 | Information Quality Assessment Framework</strong>
</p>

<p align="center">
  A systematic framework for evaluating the credibility of articles, reports, and predictions.<br/>
  一個用於評估文章、報導和預測可信度的系統化框架。
</p>

<p align="center">
  <a href="#quick-start">Quick Start</a> •
  <a href="#features">Features</a> •
  <a href="#installation">Installation</a> •
  <a href="#usage">Usage</a> •
  <a href="#license">License</a>
</p>

---

## Why This Framework?

In the age of information overload, distinguishing **signal** (valuable information) from **noise** (misleading or low-quality content) is a critical skill. This framework provides:

- A **systematic approach** to evaluate any piece of information
- **Checklists** for detecting logical fallacies and emotional manipulation
- A **scoring system** to quantify information quality
- **Domain-specific guidelines** for tech trends, investment, and industry analysis

在資訊爆炸的時代，區分「信號」與「噪音」是一項關鍵能力。本框架提供系統化的評估方法、邏輯謬誤檢測清單、量化評分系統，以及針對科技趨勢、投資分析等領域的專門指南。

---

## Quick Start

### 5-Second Check (Ask These 5 Questions)

| # | Question | What It Detects |
|---|----------|-----------------|
| 1 | Why would this person know this? | Source credibility |
| 2 | What do they lose if they're wrong? | Conflict of interest |
| 3 | What would prove them wrong? | Falsifiability |
| 4 | Do independent sources say the same? | Cross-validation |
| 5 | What's left after removing emotional words? | Information density |

**Rule**: If 2+ questions can't be satisfactorily answered, mark the information as "unverified".

---

## Features

### Six-Layer Evaluation System

1. **Source Credibility** - Author background, expertise, track record
2. **Conflict of Interest** - Financial incentives, timing with business events
3. **Argument Quality** - Logical structure, fallacy detection
4. **Evidence Quality** - Data source hierarchy (A-E levels)
5. **Prediction Quality** - Falsifiability, time-bound, probability expression
6. **Emotion vs Rationality** - Emotional word density, narrative structure analysis

### Scoring System

| Dimension | Score Range |
|-----------|-------------|
| Source Credibility | -2 to +2 |
| Conflict of Interest | -2 to +2 |
| Argument Quality | -2 to +2 |
| Evidence Quality | -2 to +2 |
| Prediction Quality | -2 to +2 |
| Emotion Ratio | -2 to +2 |
| Cross-validation | -2 to +2 |

**Total Score Interpretation**:
- **10-14**: High-quality signal - worth serious consideration
- **5-9**: Medium quality - needs further verification
- **0-4**: High noise ratio - use with caution
- **Negative**: Likely noise - consider ignoring

### Logical Fallacy Detection

- Appeal to Authority
- Slippery Slope
- Survivorship Bias
- False Dichotomy
- Appeal to Emotion / FOMO

### Emotional Word Scanner

| Category | Examples |
|----------|----------|
| Fear | collapse, disaster, crisis, catastrophe |
| Excitement | revolutionary, unprecedented, game-changing |
| Urgency | immediately, don't miss out, last chance |

**Alert threshold**: >3 emotional words per 100 words

---

## Installation

### As a Claude Custom Skill

1. Clone this repository
2. Copy the `signal-noise-skill` folder to your Claude skills directory:
   ```
   /mnt/skills/user/signal-noise-skill/
   ```
3. Start a new conversation - Claude will automatically load the skill

### Manual Reference

Simply copy the content of `SKILL.md` into your conversation with any AI assistant as a reference framework.

---

## File Structure

```
signal-noise-skill/
├── SKILL.md        # Main framework (complete 6-layer system)
├── QUICKREF.md     # One-page quick reference card (printable)
├── EXAMPLES.md     # Detailed evaluation examples
├── LICENSE         # MIT License
└── README.md       # This file
```

---

## Usage

### Trigger Phrases (for Claude Skill)

- "Is this article credible?"
- "Evaluate this claim"
- "Is this signal or noise?"
- "Analyze this prediction"
- "Check this article for logical fallacies"

### Example Output

```
## Evaluation: [Article Title]

| Dimension | Score | Analysis |
|-----------|-------|----------|
| Source Credibility | +1 | Industry CEO with 6 years experience |
| Conflict of Interest | 0 | Company benefits from AI hype |
| Argument Quality | +1 | Has timeline but slippery slope present |
| Evidence Quality | +1 | A-level sources cited |
| Prediction Quality | +1 | Time-bound but vague criteria |
| Emotion Ratio | -1 | High emotional word density |
| Cross-validation | +1 | Multiple independent sources |

**Total: 4/14** - Medium-low quality, extract facts, ignore emotional narrative
```

---

## Use Cases

- **Tech Trend Analysis** - Evaluate AI predictions, technology forecasts
- **Investment Research** - Assess financial articles, analyst reports
- **News Verification** - Check credibility of breaking news
- **Social Media** - Filter viral content for actual information value
- **Academic Reading** - Quick quality check for papers and reports

---

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request. Areas for improvement:

- [ ] Additional domain-specific checklists
- [ ] More evaluation examples
- [ ] Translations to other languages
- [ ] Integration with other AI platforms

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgments

This framework was developed through practical experience evaluating technology trends, investment analyses, and industry predictions. Special thanks to the critical thinking and epistemology communities for foundational concepts.

---

<p align="center">
  <strong>Remember: The goal is not to judge "right or wrong", but to assess "credibility".</strong>
</p>
