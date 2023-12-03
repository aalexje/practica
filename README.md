
from scipy.stats import chi2

df = 5
probabilidad = chi2.cdf(11.0705, df) - chi2.cdf(1.1455, df)

print(probabilidad)
