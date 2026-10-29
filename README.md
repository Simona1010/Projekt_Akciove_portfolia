# Optimalizácia akciového portfólia pomocou CVaR a MaxDD

Projekt sa zameriava na tvorbu akciových portfólií s rôznou úrovňou očakávaného výnosu a rizika.

Analýza využíva týždenné výnosy desiatich akcií za obdobie 2020 - 2025 a porovnáva dva prístupy k meraniu rizika: CVaR a maximálny drawdown (MaxDD).

## Obsah projektu

- získanie a spracovanie historických údajov o akciách,
- výpočet týždenných výnosov a očakávaných výnosov,
- optimalizácia portfólií pri rôznych cieľových výnosoch,
- porovnanie rizika pomocou CVaR pri 5 % hladine a MaxDD,
- vykreslenie efektívnych hraníc portfólií,
- porovnanie vlastného portfólia s optimalizovanými portfóliami.


Projekt ukazuje kompromis medzi výnosom a rizikom: portfólio s najvyšším očakávaným výnosom dosahuje aj vyššie riziko a je výrazne koncentrované do jednej akcie. Vybrané portfólio z efektívnej hranice rozkladá váhy medzi viacero akcií a ponúka vyváženejší pomer výnosu a rizika.

## Použité nástroje

R Markdown, Python cez `reticulate`, `yfinance`, `pandas`, `numpy`, `matplotlib`, `python-mip`.


