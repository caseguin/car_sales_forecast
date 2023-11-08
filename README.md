***
# Car sales predictions
***

<u>Objectif :</u>
Use the EV sales of SAAQ years 2017 and 2018 sales to train a model base ont the price and different caracteristics of the buyer.

With that model determine the sales of 2019-2022 and validate the accuracy with the real results.

Simulate the impact "Roulez vert" (subsidie) on the EV sales
Use this model to analyse the impact of a raise of the EV price on the sales.

***
<u>Data : </u>
- SAAQ immatriculation (sales)
- ISQ (demographic carateristics)
    - https://statistique.quebec.ca/fr/produit/tableau/estimation-de-la-population-du-quebec
- Guide de l'auto (price)

- Prix des bateries :
- Prix des minéraux pour les bateries :
- Évolution du prix des véhicules : https://vms.taps.anl.gov/research-highlights/u-s-doe-vto-hfto-r-d-benefits/


***
<u>Steps</u>
1. Determine the EV sales (car_sales.ipynb)
2. Web scrapping car prices (car_prices_scrapping.ipynb)
3. Merge all data (merge.ipynb)
4. Build a model (model.ipynb)
5. Predict EV sales with the model and compare to the real data
6. Generate an alternative scenario (RV) with higher prices of EV
