# Traffic Run

A 3D browser game set on a Bangalore-style street. Walk or run down the road, collect credits, jump the potholes and stones, and stay out of the way of the oncoming auto-rickshaws.

**Play:** https://okaypranjul.github.io/traffic-run/

## Controls

| Key | Action |
| --- | --- |
| ↑ ↓ | Walk |
| ← → | Turn |
| Shift | Run |
| Space | Jump |
| C | Front view |
| N | Day / night |
| M | Sound on / off |

## Run locally

The game is a single `index.html` built on three.js. It has to be served over HTTP:

```bash
python3 -m http.server 8124
```

Then open http://localhost:8124/index.html.
