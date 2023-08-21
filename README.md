# dnd-stats
[https://dnd-dice.streamlit.app/](https://dnd-dice.streamlit.app/)

## Run in Github Codespace
1. Fork the repo and start a Codespace for it.

2. Create venv and install requirements with pip:
```bash
> python -m venv .venv
> source .venv/bin/activate
> pip install -r requirements.txt
```

3. Check that Streamlit installed correctly
```bash
> streamlit hello
```
You should get a popup from VS Code that your app is running on port so-and-so. Play around with the Streamlit demo to see if things are working.

4. Run this app
```bash
> streamlit run streamlit_app.py
```

## Useful Links:
- [Streamlit documentation](https://docs.streamlit.io/library/get-started/installation#install-streamlit-on-macoslinux)
- [Probabilities for Advantage and Disadvantage](https://statmodeling.stat.columbia.edu/2014/07/12/dnd-5e-advantage-disadvantage-probability/)
- [The math of critical hits in D&D](https://www.reddit.com/r/BG3Builds/comments/157p0cl/the_math_of_critical_hits_in_dd_5e_is_critfishing/)
- [Probability and damage computation in 5E](https://docs.google.com/document/d/11eTMZPPxWXHY0rQEhK1msO-40BcCGrzArSl4GX4CiJE/edit#heading=h.5qcgsqvtvf8v)
