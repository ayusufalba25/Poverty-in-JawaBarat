# Modeling the Number of Poverty in Jawa Barat using Multiple Linear Regression with Dummy Variables

![Dashboard Overview](https://github.com/ayusufalba25/Poverty-in-JawaBarat/blob/master/images/Dashboard%20Overview.png)

This project conducted for National Data Science Tournament 2021 in Indonesia and we've managed to win the tournament as the **third winner**. Our team created a [dashboard with Tableau Public](https://public.tableau.com/app/profile/faris.dwiki.gunawan/viz/AFIB_VI/DashboardKemiskinan) based on the modeling of the number of poverty in Jawa Barat using multiple linear regression with dummy variables for each districts/cities. This particular dummy variables created to shown the marginal effect of each districts/cities in Jawa Barat to the number of poverty in its region.

Our team called **AFIB** which consider to be the abbreviations of our member that consists of:

1. [Ahmad Yusuf Albadri](https://www.linkedin.com/in/ahmad-yusuf-a-ab5696130/) (me),
2. [Faris Dwiki Gunawan](https://www.linkedin.com/in/faris-dwiki-gunawan/),
3. [Idrus Syahzaqi](https://www.linkedin.com/in/idrus-syahzaqi-9670b719b/), and
4. [Biyoso Pradnyo Purnomo](https://www.linkedin.com/in/biyoso-pradnyo-purnomo-99ba30222).

## Data
Data we've used came from ***Badan Pusat Statistik*** (BPS) that have been compiled into the **Open Data Jabar**.

## Insights
From the modeling results we can extract some insights:

* There are 5 districts that have the highest marginal effect to the number of poverty, which is *Kabupaten Bogor, Kabupaten Bandung, Kabupaten Cirebon, Kabupaten Indramayu*, and *Kabupaten Karawang*.

Districts | Estimated Coefficient
------------ | -------------
Kabupaten Bogor | 401,438418
Kabupaten Bandung | 244,401710
Kabupaten Cirebon | 223,586339
Kabupaten Indramayu | 212,567116
Kabupaten Karawang | 207,245554

* Besides of the dummy variables, there are three predictors that has significant effect on the number of poverty in Jawa Barat. There are *pengeluaran_perkapita, apk_perguruan_tinggi,* and *tingkat_pengangguran_terbuka*.

Predictors | Estimated Coefficient
------------ | -------------
pengeluaran_perkapita | -40,9845
apk_perguruan_tinggi | 8,3953
tingkat_pengangguran_terbuka | 18,3210

We've also made the coefficient and partial dependence plot in our [google colab notebook](https://github.com/ayusufalba25/Poverty-in-JawaBarat/blob/master/Code.ipynb) to gain more insight from the estimated model.
