# resumes

Eight domain-tailored resumes, all built from the same verified project history (cross-checked against GitHub + portfolio, 2026-07-24/25/26). Each is capped at 2 pages. No unproven claims, no half-finished projects, no generic filler lines.

## Which one to send

| File | Use for | Leads with |
|---|---|---|
| `resume_cv_engineer.tex` | Computer vision roles | Tennis Vision (44 stars), rPPG, DeepGuard, Field Fusion |
| `resume_mlops_engineer.tex` | MLOps / platform / infra roles | Continuum, Decifra, DeepGuard (AWS EKS), InsureML |
| `resume_ai_genai_engineer.tex` | General AI/GenAI/LLM engineer roles | Continuum, QuantaAI, VLMverse, ClinicalQwen, Parallax |
| `resume_ml_agentic_engineer.tex` | Agentic AI / autonomous-systems roles | QuantaAI, issue-resolver-agent, Continuum, Parallax, moms-verdict |
| `resume_agentic_rag_llmops.tex` | JDs that explicitly ask for agentic + RAG + LLMOps/AIOps + deployment together | Continuum, QuantaAI, issue-resolver-agent, Parallax, moms-verdict |
| `resume_research.tex` | Fellowships, research engineer roles, research labs | Continuum framed as drift-detection research (with honest limitations), issue-resolver-agent (corrigibility), moms-verdict (grounding) |
| `resume_dream_companies.tex` | Hugging Face, NVIDIA-adjacent roles | Open-source PR history first, Transformers-CV, VLMverse, MoleCuQuest (NVIDIA MolMIM), inference/quantisation work |
| `resume_general_aiml.tex` | Default/broad AI-GenAI engineer resume, no specific domain signal in the JD | Continuum, QuantaAI, VLMverse, ClinicalQwen, rPPG (fullest project spread of the eight) |

## Rules for updating these

1. **Only shipped, defensible work goes in.** In-progress projects (currently: Ratchet) stay out entirely until they're actually finished — a resume line that invites "so is this done?" in an interview is a liability, not a signal. Study/notes repos (currently: harness-engineering) are fine as a single light mention in Additional Work, never a full project.
2. **Verify before adding a stat.** Star counts, accuracy numbers, and dates get checked against the live GitHub repo, not remembered from a previous version.
3. **Cross-file consistency.** If a project's numbers change (stars, results), grep across all 6 files before considering it done.
4. **2-page limit is real.** If a new project earns a spot, something weaker leaves. Don't just keep appending.

## Compiling

No local LaTeX install. Compile via Overleaf: upload the `.tex` file, download PDF, save into `out/`.

## Source of truth for facts

`D:\outreach-engine\facts.md` holds the master verified-facts list (metrics, dates, what's real, what's explicitly NOT true). Any new resume line should trace back to it.
