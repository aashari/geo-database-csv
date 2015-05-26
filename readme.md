# Geo Database CSV #

This repository contains lists of world countries, administrative subdivision with postal Code in CSV, you can freely download and import to your database.

----------

###Database Structure###

**geo_continent**

- id 
- name
- fips


**geo_country**

- id
- id_continent
- name
- name_official
- name_native
- fips
- iso_alpha_2
- iso_alpha_3


**geo_subdivision**

- id
- id_country
- id_subdivision
- id_subdivision_type
- administrative_order
- name
- name_official
- name_native
- fips
- iso_alpha_2
- iso_alpha_3
- timezone_offset
- postal_code_start
- postal_code_end
- postal_code


**geo_subdivision_type**

- id
- name


----------

###Version Log###

**V.01**

- Initial version
	- 7 continents
	- 247 countries
	- 144,445 subdivision
	- 5 subdivision type

Detail :

-	Indonesia
	- Administrative Order 1 : 34
	- Administrative Order 2 : 514
	- Administrative Order 3 : 6998
	- Administrative Order 4 : 136118
	
	Order 1 : Province
	Order 2 : Regency / City
	Order 3 : District	
	Order 4 : Village

- Thailand
	- Administrative Order 1 : 77
	- Administrative Order 2 : 704

	Order 1 : Province / Municipality
	Order 2 : Distrct 
	