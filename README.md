# StihiData
Stihi.ru dataset for [Sberbank КлассикAI competition](https://classic.sberbank.ai/description)

Parsing was done via 'parsing.ipynb'. Proposed method is not the best one, but due to enormous number of poems in Stihi.ru it is fine. Parsing was performing for 40 hours in 8 similar jupyter notebooks (i.e. 8 pools). ~700k poems were parsed in total, after cleaning of data - ~160k poems were keeped. 

Data cleaning: 
1. Clean from 'non poems' - i.e. artefacts of parsing;
2. Keep only long poems(>3 strings in poem, >3 words in string);
3. Delete  all punctuation. 
