# PONS-CLI

Simple Command Line Interface implementation of PONS Dictionary

Work in progress, bugs are expected

![image](https://user-images.githubusercontent.com/3837916/174698644-1f559b8e-e421-433e-a68f-480ddb66cc83.png)

# Installing

1. Create and activate a free account at https://account.pons.com/en/public/signup
2. Generate a API secret key at https://en.pons.com/open_dict/public_api?logged=1
3. `git clone https://github.com/Nickguitar/PONS-CLI && cd PONS-CLI`
4. Change the value of var `secret` at line 3 to your secret key

# Usage

`./pons [-l <language1><language2>] <word>`

Ex:

- Translate the word "_pantalla_" from spanish to english:

`./pons -l enes pantalla`

- Translate the word "_helicopter_" from english to german:

`./pons -l deen helicopter`

- Translate the word "_schneiden_" using the default languages (de-en):

`./pons schneiden`

# Notes

1. The default languages are german (de) and english (en)
2. You can change the default languages in var `language` at line 9
3. Available languages: de,el,en,es,fr,it,pl,pt,ru,sl,tr,zh.
4. Not every language pair works
5. If it doesn't work (ex: `-l ende`), try reversing it (`-l deen`)

# Screenshots

![image](https://user-images.githubusercontent.com/3837916/174698789-c94e9965-005a-48ef-b879-967272f1ca1a.png)

![image](https://user-images.githubusercontent.com/3837916/174698852-c93a05cf-8f2a-42b9-be26-2a5727e13c52.png)
