
# Broker-Advisor — RL-based Broker Selector

**Short summary**  
Broker-Advisor is an RL-driven system (PPO) that selects the best broker for IoT publishers using lightweight CoAP + CBOR messages. The repo contains the simulator, training scripts, inference server, and a demo.

---

## Demo / Live preview
Add a short GIF or hosted demo here (see `/demos/demo.gif`).

---

## What’s in this repo
- `src/` — code: environment, training, inference, CoAP helpers  
- `models/` — pre-trained model weights **(not committed, see Releases)**  
- `notebooks/` — training & evaluation notebooks  
- `demos/` — demo script and example CBOR payloads  
- `results/` — evaluation results, metrics and plots

---

## Quick start (view demo)
1. Clone:
```bash
git clone https://github.com/<your-username>/broker-advisor.git
cd broker-advisor
