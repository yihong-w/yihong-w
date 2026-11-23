## Hey, I'm [Yihong Wang](https://github.com/yihong-w) 👋

![Profile visits](https://visitor-badge.laobi.icu/badge?page_id=yihong-w.yihong-w)

I work on open-source AI infrastructure, especially LLM serving and real-time voice models. Two questions I've been exploring lately: when can a scheduler reuse work across identical prompts, and how can a voice model finish its answer after the microphone stops?

### What I'm working on

| Project | Recent work |
| --- | --- |
| [SGLang](https://github.com/sgl-project/sglang) | Testing whether identical prompts can share cached KV after the first prefill. I benchmarked the scheduler change on an RTX PRO 6000 and compared output tokens, cache hits, and latency. [Scheduler PR](https://github.com/sgl-project/sglang/pull/49147) |
| [SGLang-Omni](https://github.com/sgl-project/sglang-omni) | Adding an opt-in natural finish for MiniCPM-o voice replies. I replayed the same spoken question in both modes to check whether the model finished its sentence. [Realtime inference PR](https://github.com/sgl-project/sglang-omni/pull/3428) |

---

![Yihong's GitHub activity](https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=yihong-w&theme=vue)
