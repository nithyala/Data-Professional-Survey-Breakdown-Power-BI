# Data Professional Survey — Power BI Dashboard

An interactive Power BI report analysing **630 responses** from data professionals worldwide, covering salary, tools, job satisfaction, and how hard it really is to break into the field.



<img width="1340" height="736" alt="Screenshot (444)" src="https://github.com/user-attachments/assets/80ae529f-3ec9-4c3a-8dc1-95a525886b67" />




## The Question

Anyone trying to get into data — or already in it and wondering if they're being paid fairly — runs into the same questions:

- What do different data roles actually pay?
- Which programming language do professionals really use?
- How happy are people in this field, and with *what*?
- How difficult is it to break in?

This report turns a 630-person survey into an interactive answer.

## Key Findings

### 1. People like the job. They don't like the pay.

Respondents rated their happiness (0–10) across six dimensions:

| Dimension | Score |
|-----------|------:|
| Coworkers | 5.9 |
| Work/life balance | 5.7 |
| Learning new things | 5.6 |
| Management | 5.3 |
| Upward mobility | 4.8 |
| **Salary** | **4.3** |

**Salary is the lowest-rated dimension — and 47% of respondents named "better salary" as the single most important factor if they looked for a new job today.** Remote work (20%) and work/life balance (19%) trailed well behind.

The signal is consistent: this isn't a field with a satisfaction problem. It's a field with a compensation problem.

### 2. Nearly half earn under $40k

| Salary band | Share |
|-------------|------:|
| $0–40k | 44% |
| $41–65k | 24% |
| $66–85k | 15% |
| $86–105k | 8% |
| $106k+ | 10% |

### 3. Python dominates

67% named Python their favourite language, versus 16% for R. SQL appeared frequently as a write-in.

### 4. Breaking in is easier than the internet suggests

Only **32%** found it difficult or very difficult to break into data. 43% found it neither easy nor difficult, and 26% found it easy. Notably, **59% switched careers into data** rather than starting there — this is a field people arrive at, not one they're born into.

### 5. Global, but US-heavy

United States (41%), India (12%), United Kingdom (6%), Canada (5%), with meaningful representation from Nigeria, Germany and beyond.

## Report Visuals

| Visual | What it shows |
|--------|---------------|
| KPI cards | Total respondents, average age |
| Bar chart | Average salary by job title |
| Column chart | Favourite programming language |
| Treemap | Country of survey takers |
| Gauge ×2 | Happiness with salary, happiness with work/life balance |
| Donut chart | Difficulty breaking into data |

## Data

- **Source:** Data Professional Survey (Alex The Analyst community survey)
- **Respondents:** 630
- **Collected:** 10–26 June 2022
- **Fields:** 28 — role, salary band, industry, favourite language, six happiness ratings, difficulty breaking in, job priorities, demographics

## Tools & Techniques

- **Power BI Desktop** — data model, measures, report design
- **Power Query** — cleaning free-text write-ins, standardising salary bands, splitting "Other (Please Specify)" responses
- **DAX** — average salary measure from banded categories, happiness averages, respondent counts
- Custom theme, gauges, treemap, and slicer-driven interactivity

## Repository Structure

```
.
├── README.md
├── report/
│   └── Data_Professional_Survey_Project.pbix
├── data/
│   └── Power_BI_Final_Project.xlsx
└── images/
    └── dashboard.png
```

## How to Use

1. Download `report/Data_Professional_Survey_Project.pbix`
2. Open in [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free)
3. Use the slicers to filter by role, country, and salary band

## Next Steps

- Segment happiness scores by salary band — does pay actually buy satisfaction?
- Compare career-switchers vs. non-switchers on salary and difficulty
- Normalise salary by country to control for cost of living

## Author

**Nithyalakshmi Jambulingam**
