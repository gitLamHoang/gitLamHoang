# Hi, I'm Lam Phan.

**Stanford CS · Class of 2030**

I build tools for questions hidden in messy data: where a forecast fails, which date a reviewer should trust, and whether a model can generalize beyond the people it learned from.

My projects connect data work to an interface or workflow someone can try. I'm interested in applied AI, useful products, and learning from the people who would use them.

**Start with the [NYC forecast explorer](https://gitlamhoang.github.io/nyc-mobility-intelligence/)**, or follow the [two-minute project tour](https://github.com/gitLamHoang/gitLamHoang/blob/main/TOUR.md).

### NYC Mobility Intelligence

**Where does a taxi-demand forecast help—and where does it miss?**

An interactive map connects official NYC taxi records to hourly forecasts across **262 zones**. Explore 48 historical hours, compare models, and inspect errors by place and time. Behind the interface: an audited data pipeline, chronological evaluation, delayed-observation experiments, and a local prediction API.

Python · TypeScript · SQL · CSS

[Explore the map](https://gitlamhoang.github.io/nyc-mobility-intelligence/) · [Code and setup](https://github.com/gitLamHoang/nyc-mobility-intelligence) · [Measured tradeoffs](https://github.com/gitLamHoang/nyc-mobility-intelligence/blob/main/reports/LATENCY_REVIEW.md)

*The map shows April 2026 validation data, not live forecasts. May remains sealed for final evaluation.*

### Document Date Review

**How can extracted dates stay connected to their source and a human decision?**

A document-processing prototype that extracts dates with context, retrieves relevant passages, and stores a review queue with an audit history. SQLite makes decisions persistent across runs; versioned indexing keeps changed documents distinguishable.

Python · SQL / SQLite

[Code and runnable demo](https://github.com/gitLamHoang/pharma-ocr-date-rag) · [Behavior tests](https://github.com/gitLamHoang/pharma-ocr-date-rag/tree/main/tests)

*Public examples are synthetic. This prototype does not make pharmaceutical release decisions.*

### EEG State Classifier

**Does a signal classifier work beyond familiar participants?**

A signal-processing and SVM pipeline with reproducible feature extraction, participant-disjoint evaluation, and grouped model tuning. Synthetic fixtures make the workflow inspectable without exposing participant recordings.

Python · SciPy · scikit-learn

[Code and runnable demo](https://github.com/gitLamHoang/Classfying-brain-wave-state) · [Collection protocol](https://github.com/gitLamHoang/Classfying-brain-wave-state/blob/main/docs/hardware_protocol.md)

*Synthetic results demonstrate the pipeline, not real-world or clinical accuracy.*

---

I like small, complete workflows: a clear question, a baseline, a working demo, and an honest account of what still needs testing.

[LinkedIn](https://www.linkedin.com/in/phanhlam)
