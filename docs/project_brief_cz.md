# Analýza prodejů automobilů v USA

## Zadání projektu

Tentokrát budeme analyzovat data z automobilového sektoru. Cílem je dozvědět se více o vozech, které byly prodávány ve Spojených státech v roce 2019.

Dataset obsahuje seznam automobilů popsaných 31 různými parametry.

## Popis proměnných

- `car_id` – identifikátor vozu
- `manufacturer` – výrobce automobilu
- `model_year` – rok uvedení modelu
- `category` – typ vozu
- `msrp` – výrobcem doporučená maloobchodní cena (v dolarech)
- `mpg` – průměrná spotřeba paliva v mílích na galon
- `engine` – typ motoru
- `drivetrain` – typ pohonu
- `passenger_capacity` – maximální počet cestujících
- `passenger_doors` – počet dveří
- `base_curb_weight` – celková hmotnost vozidla
- `wheelbase` – vzdálenost mezi středem přední a zadní nápravy
- `height` – celková výška vozu (v palcích)
- `fuel_tank_capacity` – kapacita palivové nádrže (v galonech)
- `net_torque` – optimální točivý moment
- `net_horsepower` – výkon generovaný na klikovém hřídeli motoru
- `displacement` – zdvihový objem motoru
- `trans_type` – typ převodovky
- `brakes_abs` – zda je vůz vybaven ABS
- `front_suspension` – typ předního odpružení
- `rear_suspension` – typ zadního odpružení
- `traction_control` – zda je vůz vybaven systémem kontroly trakce
- `parking_aid` – zda je vůz vybaven parkovacími senzory
- `tire_pressure_monitor` – zda je vůz vybaven snímači tlaku v pneumatikách
- `backup_camera` – zda je vůz vybaven couvací kamerou
- `stability_control` – zda je vůz vybaven stabilizačním systémem
- `basic_years` – počet let záruky
- `turning_diameter` – průměr otáčení (ve stopách)
- `front_tire_width` – šířka předních pneumatik (v milimetrech)
- `front_tire_rim_size` – velikost předních ráfků (v palcích)

## Hlavní analytické otázky

1. Kolik vozů bylo nabízeno v roce 2019?
2. Kolik vozů bylo nabízeno podle stáří, tedy podle rozdílu mezi rokem prodeje a modelovým rokem? Kolik vozů je starších než 10 let?
3. Kolik aut prodává každý výrobce?
4. Produkují výrobci více aut s většími motory, nebo s menšími motory? Existuje vztah mezi zdvihovým objemem motoru a modelovým rokem vozu?
5. Jaký je vztah mezi průměrnou spotřebou paliva a zdvihovým objemem motoru? Které auto má největší zdvihový objem motoru? Jaká je jeho průměrná spotřeba? Které auto je nejúspornější?
6. Závisí cena auta na jeho výkonu? Jaký výkon má nejsilnější nabízené auto?
7. Existuje vztah mezi dojezdem vozu a jeho celkovou hmotností nebo odporem vzduchu, který může souviset s výškou auta?

## Doplňující úkol
Navrhněte také vlastní doplňující otázky, které mohou rozšířit analýzu a přinést další zajímavé insighty o vozech prodávaných v roce 2019.
