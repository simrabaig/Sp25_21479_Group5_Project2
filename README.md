# Sp25_21479_Group5_Project2

# Team Name: 
21479 Group 5 

# Team Members:

1. Simra Baig [@simrabaig](https://www.github.com/simrabaig)
2. Miranda Gonzalez [@mag93887](https://www.github.com/mag93887)
3. Terri Morrison [@terrimorrison28](https://www.github.com/terrimorrison28)
4. William Barrett[@Wbarrett1013](https://www.github.com/Wbarrett1013)
5. Matthew Willbanks [@Mwilbanks22](https://www.github.com/Mwilbanks22)

# Database information:
  The dataset, “Chemicals in Cosmetics,” contains 114,636 rows and 22 columns, providing detailed information reported to the California Safe Cosmetics Program (CSCP) under the California Department of Public Health (CDPH). It includes fields such as CDPH ID, product name, company and brand names, product categories, chemical identifiers (CAS IDs and numbers), chemical names, and key reporting and reformulation dates.
  This dataset captures cosmetic and personal care products sold in California that manufacturers, packers, or distributors have reported as containing ingredients known or suspected to cause cancer, birth defects, or other developmental or reproductive harm. 
  The purpose of the dataset is to make information about hazardous or potentially hazardous ingredients publicly accessible. However, it may not include all relevant products due to potential underreporting by companies.



# Contextual Landscape
  The cosmetic industry faces increasing scrutiny because of serious health risks tied to certain ingredients in beauty products. Some chemicals commonly used — like heavy metals (lead, arsenic) — are linked to cancer, neurological damage, and hormonal system disruptions. These risks are especially concerning because the primary users are women, and the chemicals can negatively impact fertility and the hormone cycle.
  Additionally, the U.S. FDA does not require pre-market safety testing for most cosmetic ingredients. This regulatory gap means harmful substances can enter the market and accumulate in the body over time without thorough oversight.
  However, there’s a growing shift: consumers are demanding cleaner, more transparent beauty products, leading to the rise of eco-friendly, non-toxic, and vegan cosmetic brands. Some countries are even taking legislative action, banning or restricting the use of toxic ingredients. This shows a clear divide between the traditional, often unregulated use of chemicals and the new, health-conscious market expectations.


# Question 1 - Within the subcategories of nail and hair products, is there significant overlap in the top 20 chemicals used?

![F03BA12D-3483-4092-AAA8-5895D5BF0E12](https://github.com/user-attachments/assets/a5e88848-0493-4332-bf2f-e44070959b08)



### Rationale 
  -  Identifies the most commonly used chemicals across different product subcategories.
  -  Highlights potential repeated exposure risks for consumers.
  -  Reveals the extent of standardization or limitation in ingredient choices.
  -  Provides insights into broader industry trends in cosmetic product formulation.

  We chose this question because we were curious to see whether there is a significant overlap in the chemicals used across different subcategories of cosmetic products. Understanding this overlap can reveal how standardized or limited ingredient choices are within the industry. Additionally, identifying commonly repeated chemicals could shed light on potential cumulative exposure risks for consumers, particularly to ingredients known or suspected to cause harm. By analyzing these patterns, we can better understand trends in cosmetic formulation practices and potential areas for public health concern.


### Manipulations
  For the visualization, we filtered the dataset to include only hair and nail product subcategories. We then limited the data to focus on the top 20 most frequently reported chemicals across these products. To improve readability and highlight trends or outliers, we color-coded each chemical name, allowing for easier comparison of chemical usage across different subcategories.

### Analysis
![2645E04A-47C4-4EC9-A27A-BA4CAF35ECB7](https://github.com/user-attachments/assets/ba752d7b-af47-417b-9206-ee0cf595e282)

  The visualization shows that titanium dioxide is a dominant chemical appearing across both hair and nail product subcategories. In hair products, titanium dioxide is primarily used for pigmentation and UV protection, while in nail products, it contributes to opacity and brightness.
  Its widespread presence across multiple subcategories reflects common formulation strategies focused on color enhancement, product stability, and sun protection. This indicates that cosmetic manufacturers frequently rely on the same key ingredients across product lines, reinforcing trends toward standardized formulations.
  From a consumer health perspective, the repeated appearance of titanium dioxide across categories highlights the potential for cumulative exposure. Although titanium dioxide is generally valued for its functionality, concerns exist — particularly regarding inhalation of its fine particulate form, which has been linked to adverse health effects. The overlap shown in the visualization emphasizes the need to evaluate cross-product exposure risks, not just risks tied to individual products.



# Question 2 - Are there any trends in hazardous materials in products from 2009 to 2020, and which product types show the greatest increase or reduction?
![Image 4-27-25 at 8 45 PM](https://github.com/user-attachments/assets/df63cda6-c3d0-4030-ad48-77c6e05f19ec)


### Rationale 
  -  Reveals overall trends in the use of hazardous materials in cosmetics over time (2009–2020).
  -  Highlights which product categories have contributed most to increases or decreases.
  -  Identifies which types of cosmetic products currently contain the highest or lowest levels of hazardous materials.
  -  Shows whether hazardous material usage is trending upward or downward by product type.
  -  Provides insights into the potential impact of regulations implemented during this period.
    
We found this question compelling because it helps us understand whether the use of hazardous materials in cosmetic products has generally increased or decreased over time. By analyzing trends from 2009 to 2020, we can pinpoint which product categories have driven these changes and which products contain the highest or lowest levels of hazardous materials today. Additionally, this analysis allows us to infer the possible effects of regulatory actions taken over the years and how they may have influenced industry practices related to hazardous ingredient usage.


### Manipulations
  The second visualization incorporates filters that emphasize the most toxic chemicals, and each one is distinguished by a unique color. The legend on the left side of the visualiztion dsplays those colors. We also made sure to manipulate the rows' data to be a distinct count of the product name. The reason we chose to use fewer selected chemicals was to allow the visualization to appear less overwhelming and clearer to understand when viewing. 


### Analysis - Trends in Toxic Chemicals 


![AGV_vUfZP6bcAgzr9MaNUd_DGB1ZDuQVEk7DlLZIIvmaykdA8_njho0hI2Fnih6JC2AxT1NMGZO1kyQbSI_1D6BXvLuk0H4dJW1K7l42UfGsSKKtbIMdiLpaUclrHM9oJdxolEZEvNcf=s2048](https://github.com/user-attachments/assets/cf497927-89f8-40da-a0b6-913268867be9)

#### 1. Butylated Hydroxyanisole (BHA)
  -  Classified as a carcinogen.
  -  Significant decrease in product use from 2009 to 2020.

# 
![AGV_vUcd3vgNx_EhZIm08z-0Un9Zpn_nU-_9n9HoUTuG49jz5WbIQsRK8u3QcnsrUdwwnLAOT-YmorMXtVOMwhyH53pYrZaZsGTS-lA8_pcgVN92Uc0Wi7TW9tGlW44laMHJpI0IE5cQ=s2048](https://github.com/user-attachments/assets/723a2cde-562d-40db-a3c8-b3fce8539b26)

#### 2. Triethanolamine
  -  Causes allergic reactions (skin and eye irritation) and potential toxicity over long-term exposure.
  -  Reported in 2009; discontinued by 2018.

# 
![AGV_vUfUkojlxebbOudBxJC-kQ7-lodNVJ15_CyFpGa1zzx6AHFpDxmevHu39ViReLiPTy29yKwh_owxrIs7Dtnrmgip_ysT2ZhiWzQk63OnwTgjYKvy65pf7P0g9KoETtTZSWZoTbAU=s2048](https://github.com/user-attachments/assets/11c319e8-6f98-4566-9463-dcc3c28ccece)

#### 3. Estragole
  -  Naturally found in basil oil; proven carcinogenic in studies.
  -  Sharp decline in use between 2009 and 2020.

# 
<img width="728" alt="AGV_vUd7WMBRxnfMjEahx99xfYWYHXaUnL6l_KWSZGlZkJtC-gaRnLpKD77uQigBgBH4Namxw6WHVIb17YLIvKdSYplZsbRB-NI848Q_R9I0oipyd-8vaH4DlC28vnuI5yQDRm41f5W6MQ=s2048" src="https://github.com/user-attachments/assets/7b99aa22-2492-4be8-971e-c223a28d17d7" />

#### 4. Cocamide DEA (Bright Orange) / Cocamide MEA (Light Orange) / Lauramide DEA (Dark Yellow)
  -  Associated with cancer risk.
  -  Cocamide DEA was briefly discontinued after 2009 but reappeared by 2020.
  -  Cocamide MEA reported in 2012, phased out by 2018 but seen in some 2020 products.
  -  Lauramide DEA introduced in 2011 and discontinued by 2013.

# 
![AGV_vUcBwhdOA3y_PHsXjx6ZxYdSec92bAOLeL2mB3gIPr_wBoA2gaAsySstve92009BLS4Gf-RIv7MJHHuSKQc2KW-k4_pX-xuHC0DabrvlAPO_hVLI_2Knk54ywIHD2X8XFez3DvTZpw=s2048](https://github.com/user-attachments/assets/f97d7200-7b4c-4ca7-806a-80560f2a7edd)

#### 5. Retinol - Highest Trend of Usage
  -  Popular for anti-aging, but linked to skin cancer (especially with UV exposure) and reproductive harm.
  -  Highest usage trend, though declining after 2019 as awareness grows.

# 
<img width="709" alt="IMG_5869" src="https://github.com/user-attachments/assets/d201de1c-3159-4f63-b8fe-81ad53093604" />

#### 6. Pulegone - Lowest Trend of Usage
  -  A toxic compound linked to liver and lung cancers.
  -  Very low trend of use, only reported between 2015 and 2016.

# 
<img width="572" alt="PNG image" src="https://github.com/user-attachments/assets/774150ef-f16b-468c-8430-9fd0e31593f1" />

#### 7.   Progesterone
  -  Linked to skin irritation, headaches, and cancer risk.
  -  Reported use from 2009 to 2014, then discontinued.

# 
<img width="486" alt="PNG image" src="https://github.com/user-attachments/assets/53736d36-5f46-428a-9f74-537000d175fa" />

#### 8. Di-n-butyl Phthalate (DBP)
  -  Can cause birth defects and reproductive toxicity.
  -  Sharp rise in 2010, discontinued after 2016.

# 
<img width="419" alt="PNG image" src="https://github.com/user-attachments/assets/992e4fc0-ae48-4028-9caf-5fdcade5b6db" />

#### 9. Bisphenol A (BPA)
  -  Known for causing brain development issues, cardiovascular risks, and infertility.
  -  Reported presence in products starting in 2019, with with inconclusive results on whether or not it has been discontinued recently.

# 
<img width="463" alt="PNG image" src="https://github.com/user-attachments/assets/d0ec7b9f-9b45-4dcb-9dcf-8b1299f245c2" />

#### 10. Spironolactone
  -  Associated with stomach issues, cardiac irregularities, and allergic reactions.
  -  Briefly reported in 2010; discontinued the same year.


# Tableau Packaged Workbook






