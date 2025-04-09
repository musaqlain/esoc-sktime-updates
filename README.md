# esoc-sktime-updates

# this message is for esoc '25 decision makers. thanks

successfully added _update method on ExponentialSmoothing but since my implementation uses pd.concat() to combine data, since pandas v2.0 has removed the .append() method. It follows the full refit approach because the underlying statsmodels ExponentialSmoothing model does not support true incremental updates.

I am getting some errors, after fixing them i will raise pr for that too.
