# Retail-trading-activity-on-the-underlying-and-option-skewness-a-term-structure-perspective
Option skewness is considered a valid measure of distinction between a smile and a smirk. In performing a PCA analysis on the correlation for the skewness for different maturities, the author identifies different clusters of skewness:
  monthly options (10, 20 and 30 days)
  60 days options
  90 days options
  120 to 180 days options.
A possible explanation might be the retail trading activity on the underlying stock. Effectively, not only retail trading activity, when properly measured, has an explanatory power on the skewness of the underlying, but a clear term-structure trend emerges, with parameters changing magnitude and sign at different maturities. Additionally, an event study on the impact of the stay-at-home mood on the skewness term structure was carried out. Three phases were questioned: the pandemic shock, the pandemic exit effect and the after-pandemic one. There is, in conclusion, clear evidence of the propagation of the retail trading activity up to the term structure of skewness of the options market. This happens mainly through the channel of the activity and the combined effect of activity and sentiment.
MATFILE= matlab file showing structural break (pandemic, post pandemic and after pandemic)+
MATFILE cross = as MATFILE but with interaction term
CROSSSPY = models with market skewness (SPY) and interaction
NOCROSSSPY = models with market skewness (SPY)
CROSSSNASDAQ = models with market skewness (NASDAQ) and interaction
NOCROSSNASDAQ = models with market skewness (NASDAQ) and no interaction
Immagini = identifies an immagine folder, showing graphically the magnitude, but not the significance, of the structural break.
Immagini_effetto_skewness = shows the impact of the pandemic and of the post-pandemic on the y, the risk-neutral skewness.
