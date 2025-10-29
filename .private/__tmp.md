# Zdravotní dotazník / zkoumání
Ve složce /koop je sada pdf.

Je to přepis z webové služby, která postupně dotazuje a vyhodnocuje klientovo zdraví.

## Převod ZD do funkčního stromu
Potřebuju vytvořit pavouka/strom se všemi větvemi a poli pro vepsání údajů podle přiložených pdf/obrazů.

Tento pavouk se pak použije pro detekci, jak přesně vyplnit ZD, kam přesně vepsat jaké informace z reálných diagnóz a událostí o klientovo zdraví do tohoto stromu / do konkrétních polí.

Pavouk musí obsahovat VÝHRADNĚ reálná pole ze zdroje, ne technická metadata.
Čili například pro 'question: "Výška (cm)"' existuje v pavoukovi REÁLNĚ pouze pole 'answer: text-field', ne ŽÁDNÉ 'type: "number"' a/nebo 'unit: "cm"'.

Veškeré volby odpovědí ze zdroje a případné pole pro "ruční" zápis informací musí být v pavoukovi zastoupeny. Systém musí PŘESNĚ vědět, která pole/volby v pavoukovi existují, pro rozhodnutí, co/kde PŘESNĚ má být zvoleno/zapsáno.

###
Použij nejvhodnější kompaktní formát pavouka/stromu → yaml/toml/...?

###
Jsou ve výstupu veškeré body (číslované i nečíslované položky) jako ve zdroji? Včetně číselných označení?

###
Tzn:
- 'answer: "checkbox"':
    - NE: toto NEJSOU konkrétní volby odpovědi
- 'text_field: "Uveďte o jaké onemocnění se jedná"'
    - NE: tohle má být 
    - 'question/požadavek: "Uveďte o jaké onemocnění se jedná"'
    - a cca 'answer-field: ""'
