# Assignment Writeup

## Proposition
**"Global fossil fuel subsidies are declining."**

This proposition was chosen because the IMF Fossil Fuel Subsidies dataset contains data that can genuinely support either interpretation depending on which metrics, countries, time periods, and subsidy types are highlighted.

---

## Visualizations Supporting "Subsidies ARE Declining" (Page 1)

### Design Decisions

#### Decision 1: Truncated Y-Axis on US Subsidies Chart
**Score: -1.5 (Deceptive)**

The Y-axis starts at $700 billion instead of $0, making the 12% decline from $860B (2019) to $757B (2022) appear visually dramatic—occupying nearly 60% of the chart height. This is a well-known deceptive technique that exaggerates the magnitude of change. While the actual decline is real, starting the axis at zero would reveal that subsidies remain at historically high levels. I considered using a broken axis indicator but omitted it to maximize the persuasive effect.

#### Decision 2: Cherry-Picked Countries for "Leading Nations"
**Score: -1 (Deceptive)**

I selected only 5 countries (US, Canada, France, Brazil, Estonia) that show declining subsidies as % of GDP, while omitting the 136 countries where subsidies increased. The label "Leading Nations" implies these are representative examples rather than carefully selected exceptions. This survivorship bias is deceptive because it suggests a global trend that doesn't exist.

#### Decision 3: Selective Time Period (2019-2023)
**Score: -1 (Deceptive)**

By starting the US line chart at 2019 (a local peak) rather than 2015, the visualization captures a decline that might simply be normal fluctuation. If I had shown 2015-2023, the audience would see that 2022's $757B is higher than 2015's $730B—a different story entirely.

#### Decision 4: Focusing on Explicit Subsidies (2022-2023 drop)
**Score: -0.5 (Slightly Deceptive)**

The supporting chart highlights how explicit subsidies dropped 41% from 2022 to 2023, but frames the 2022 spike as an "energy crisis anomaly" rather than acknowledging that 2023 levels ($782B) are still 38% higher than 2019 ($567B). This framing dismisses inconvenient context.

#### Decision 5: Positive Framing in Titles
**Score: -1 (Deceptive)**

Titles like "Progress on Climate" and "America Leads the Way" inject editorial judgment that isn't supported by the full picture. These titles prime the viewer to interpret the data positively before examining it critically.

---

## Visualizations Supporting "Subsidies are NOT Declining" (Page 2)

### Design Decisions

#### Decision 1: Y-Axis Starts at Zero
**Score: +2 (Fully Earnest)**

The main chart starts the Y-axis at $0, showing the full magnitude of global subsidies ($4.4T → $7.0T → $8.2T projected). This honest scale reveals that subsidies have grown 58% since 2015 and are projected to reach $8.2 trillion by 2030.

#### Decision 2: Complete Time Series (2015-2030)
**Score: +1.5 (Earnest)**

Rather than cherry-picking time periods, I show all available years including IMF projections through 2030. This gives viewers the full context to make informed judgments. The projections are clearly labeled as such.

#### Decision 3: Including Both Actual and Projected Data
**Score: 0 (Neutral)**

While including projections is transparent (they're labeled), showing alarming growth through 2030 emphasizes worst-case scenarios. The IMF projections assume current policies continue, which may or may not occur.

#### Decision 4: Dramatic Title ("Crisis")
**Score: -0.5 (Slightly Deceptive)**

Using "crisis" is editorial, though arguably data-supported given the magnitude ($7 trillion annually, growing). Still, it primes viewers toward alarm rather than neutral assessment.

#### Decision 5: Showing All Top Emitters' Growth
**Score: +1 (Earnest)**

The supporting bar chart shows growth rates for the 5 largest emitters without excluding any. It honestly shows that India (+93%), China (+85%), and Japan (+55%) have substantially increased subsidies, while the US (+4%) has been relatively flat.

---

## Which Side Am I Leaning Toward?

The visualizations arguing that subsidies are **NOT declining** present a more honest picture of global reality. While specific countries or metrics may show decreases, global fossil fuel subsidies have increased by 58% since 2015 and are projected to reach $8.2 trillion by 2030. The "declining" visualizations require significant cherry-picking of countries, time periods, and metrics to sustain their argument.

---

## Deceptive Techniques Summary

**"Declining" visualizations:**
- Truncated Y-axis (makes 12% drop look like 60% visually)
- Cherry-picked countries (5 declining out of 168)
- Selective time period (peak-to-trough framing)
- Framing 2022 as "anomaly" to dismiss context
- Editorially positive titles

**"Not Declining" visualizations:**
- Dramatic/alarming title ("Crisis")
- Emphasis on projections that may not occur
- Use of absolute USD (larger numbers) rather than % GDP

---

## Final Reflection

The process of creating these opposing visualizations revealed how malleable data can be in the hands of a motivated visualizer. What surprised me most was how easy it was to construct a compelling "declining" narrative despite the data clearly showing the opposite trend globally. By focusing on the United States, selecting a peak-to-trough time period, truncating the Y-axis, and cherry-picking countries with declining percentages, I could construct a chart that would likely persuade a casual viewer that progress is being made—when the full picture shows subsidies nearly doubling since 2015.

Creating the "earnest" visualization (subsidies increasing) also taught me that even honest choices carry persuasive weight. Starting the Y-axis at zero is considered best practice, but it also happens to make the growth look more dramatic. Using absolute dollars rather than percentage of GDP results in larger, more alarming numbers. Including projections through 2030 shows the trend continuing, but projections are inherently uncertain. Even my choice to use red coloring—associated with danger and alarm—is a persuasive choice.

I now define "ethical analysis and visualization" as the commitment to (1) not actively misleading viewers through techniques like truncated axes or cherry-picked data, (2) providing appropriate context that allows viewers to evaluate claims critically, and (3) being transparent about choices that could influence interpretation. The line between "acceptable persuasion" and "misleading" is not always clear, but I would draw it at intentional omission of contradictory evidence and techniques (like truncated axes) that exploit visual perception to exaggerate effects. A good test: would I be embarrassed if a viewer discovered what I omitted or manipulated? If yes, it's probably over the line. The visualizations supporting "declining" subsidies failed this test; the "not declining" visualizations, despite their alarming framing, presented the full data honestly.
