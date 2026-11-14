## Ansh Gosain

**Affiliations:** University of Pennsylvania, Neuroscience & Computer Science, Class of 2028

---

### Abstract

Most real-world signal arrives incomplete or in fragments: scattered public records, noisy audio, partial surveillance data on an overdose crisis. I build systems that work anyway. Right now that means an AI agent that answers drug-development questions with every claim traced to a public record, a browser tool that reads tempo and key from raw audio to plan DJ sets, and agent-based simulations of the opioid overdose crisis in Kensington. More broadly, I am interested in learning-based models of neural and behavioral data, the kind that turn noisy recordings, scans, and behavior into something you can act on, whether that ends in a mechanism, a diagnosis, or a restored function.

### Methods

```python
class Ansh:
    languages = ["Python", "JavaScript", "SQL", "Java", "OCaml", "R", "MATLAB"]
    tools     = ["GCP (Cloud Run, Cloud SQL, Vertex AI)", "Gemini + ADK", "Postgres + pgvector",
                 "FastAPI", "Docker", "OpenTelemetry", "Web Audio API", "NetLogo", "DeepLabCut"]
    domains   = ["agentic AI", "computational neuroscience", "simulation", "signal processing"]

    def approach(self, problem):
        """Decode before you diagnose. One signal is a symptom; several are a system."""
        signals = [m for m in modalities(problem) if measurable(m)]
        return model(integrate(signals)) if signals else instrument(problem)
```

### Experiments

| Project | Question | Result | Status |
|---|---|---|---|
| [NeuroScope](https://github.com/gosainansh8/neuroscope) · [live demo](https://neuroscope-api-561220657386.us-central1.run.app) | Can an AI agent answer Alzheimer's, Parkinson's, and ALS drug-development questions with every claim traced to a public record? | Unified 9,815 trials, 7,838 PubMed abstracts, and FDA, EMA, and SEC records. On a 66-question benchmark, a single Gemini agent matched a multi-agent team's accuracy at a 13.2 s median response versus 29.7 s, for half the cost. | Live |
| [SetFlow](https://github.com/gosainansh8/setflow) · [live demo](https://gosainansh8.github.io/setflow/) | Can a browser read tempo and key from raw audio well enough to plan a DJ set? | BPM and key detection in a Web Worker with half-time correction and key confidence, feeding a beam-search sequencer that balances tempo, harmonic fit, and energy. Runs entirely in the browser. | Live |
| Kensington ABM | Can we simulate overdose dynamics well enough to test interventions? | GIS-integrated simulation across 13 treatment sites. In simulation, housing instability was linked to 8% higher mortality and 33% lower treatment enrollment. | In progress |
| TMS/fMRI Pipelines | Can stimulation and imaging be aligned cleanly enough to trust the readout? | Standardized neuroimaging data to BIDS across 9 scan targets for depression studies, and improved TMS coil targeting accuracy by about 30%. | Complete |

### Discussion

Interested in where life sciences, technology, and healthcare meet. More specifically, the parts of healthcare that fail for engineering reasons rather than scientific ones: data that exists but can't be searched, models that can't be trusted without a source, and tools that never leave the lab.

### Correspondence

[agosain@sas.upenn.edu](mailto:agosain@sas.upenn.edu) · [LinkedIn](https://www.linkedin.com/in/ansh-gosain-88467522a/)
