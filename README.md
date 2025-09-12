# LoPAS – Local-Personal AI System

LoPAS is the world’s first **personal indicator framework** that quantifies human states 
and contexts (individual → organization → society → civilization) 
in a unified way.

## 🌟 Key Indicators
- **DoQ (Density of Questions)** – quality of problem recognition
- **CCI (Connectivity Index)** – cognitive / cultural linkage
- **RDI (Reasoning Divergence Index)** – branching ability
- **HRI (Hypothesis Reframing Index)** – reframing power
- **TRS (Total Resonant Score)** – fatigue / recovery balance
- **RVI (Restoration Value Index)** – adaptation & restoration
- **SCI (Structural Collapse Index)** – systemic risk
- **AHI (Altruism-Harvest Index)** – altruism & circulation

## 🚀 Features
- **API**: Cloudflare Worker endpoint `/api/score`
- **Demo UI**: [LoPAS demo](https://hanabokur0.github.io/lopas-demo/)
- **MCP Adapter**: `lopas_http_mcp.py` bridges LoPAS with Claude/ChatGPT

## 🧭 Example Usage
Send JSON to `/api/score`:

```json
{
  "inputs": {
    "DoQ": {"questionCount": 12, "struct": 70, "diversity": 65, "integration": 75},
    "TRS": {"fatigue": 30, "recovery": 70, "reward": 60, "meaning": 80}
  }
}
