# Kooperativa - zdravotní zkoumání
https://knz.koop.cz/KoopLifeWeb/faces/p1FN/tab_main.xhtml#

## Legenda
{A}, {B}, → {Z}: označení kapitoly
<male|female>: celá vnořená sekce platí pouze pro uvedené pohlaví
{1}, {2}, → {x}: číslo odpovědi pro otázku v dané v sekci (kontext/začátek otázky může být i na předcházejících vyšších úrovních)
  […]: pole na vyplnění odpovědi textem
  [a|b|→|z]: volba z možných odpovědí
{1+}, {1-}, {1?}: číslo otázky a zástupné symboly odpovědí: [Ano|Ne|Nevím]
{1a}, {1b}, → {1z}, {1ade}: číslo otázky a pořadí odpovědi(í) při volbě ze seznamu [a|b|→|z] pro stromové pokračování
[…]\n```md blok```: seznam položek, ze kterého se vybírá do […]

Dočasné pracovní:
{…}, {…+}, ...: místo pro doplnění čísla odpovědi

## {A} Dotazník pro slevu za zdravý životní styl
{1} Mám zájem o vyplnění dotazníku pro slevu za zdravý životní styl [Ano|Ne]
{2} Výška (cm): […]
{3} Váha (kg): […]
{4} Kouříte nebo jste kouřil/a **v posledních 2 letech**? (Kouřením rozumíme užívání tabáku nebo elektronických cigaret) [Ano|Ne]
{5} Pijete nebo jste pil/a denně alkohol v množství větším než 2 l piva, 0,5 l vína nebo 0,1 l lihovin? [Ano|Ne]
{6} Užíváte nebo jste užíval/a drogy či jiné návykové látky? [Ano|Ne]
{7} Kolik hodin průměrně denně spíte? [Méně_než_6_hodin|6_až_9_hodin|Více_než_9_hodin]
{8} Jak často se věnujete pohybu? [Vůbec_nebo_velmi_zřídka|Nepravidelně_v_průměru_1x_týdně|Pravidelně_min._2x_týdně]
{9} Jak často chodíte na preventivní lékařské prohlídky k praktickému lékaři? [Minimálně_1x_za_2_roky|Méně_často_než_1x_za_2_roky|Vůbec]

## Zdravotní dotazník

### {B} Základní dotazy o pojištěném
{1} Praktický lékař - Jméno a příjmení, adresa (pokud neznáte přesnou adresu, uveďte město): […]
{2} Výška (cm): […]
{3} Váha (kg): […]
{4} Kouříte nebo jste kouřil/a **v posledních 2 letech**? (Kouřením rozumíme užívání tabáku nebo elektronických cigaret) [Ano|Ne]
{5} Pijete nebo jste pil/a denně alkohol v množství větším než 2 l piva, 0,5 l vína nebo 0,1 l lihovin? [Ano|Ne]
{6} Užíváte nebo jste užíval/a drogy či jiné návykové látky? [Ano|Ne]
  {6+} Které z následujících drog jste užil/a?
    {7} Marihuana - kouření, vaporizace, konzumace [Ano|Ne]
      {7+}{8} Užil/a jste tuto drogu **v posledních 2 letech**? [Ano|Ne]
        {8+}{9} Jak často jste **v posledních 2 letech** užíval/a tuto drogu? [1-2krát_týdně_nebo_méně|3-4krát_týdně|5krát_týdně_nebo_více]
    {10} Jiný druh drog (např. kokain, opiáty, heroin, amfetaminy, MDMA, pervitin) [Ano|Ne]
      {10+}{11} Užil/a jste tuto drogu v posledních 7 letech? [Ano|Ne]
{12} Jste nebo jste byl/a závislý/á na alkoholu, drogách, léčivých přípravcích nebo jiných návykových látkách? [Ano|Ne]
  {12+}{13} Užil/a jste **v posledních 10 letech** některou z výše uvedených látek? [Ano|Ne]

### {C} Onemocnění - část 1
#### 1. Máte nebo jste měl/a některé z následujících onemocnění, kvůli kterým vás lékař **vyšetřoval, sledoval nebo léčil**?
{…} 1.a) Nádorová onemocnění (např. rakovina – zhoubný nádor, leukémie, lymfom, nezhoubný nádor mozku) [Ano|Ne]
  {…+}
    {…} Rakovina – zhoubný nádor [Ano|Ne]
      {…+}
        {…}<male> Prostaty [Ano|Ne]
          {…+}{…} Prodělal jste toto onemocnění **v posledních 10 letech**? [Ano|Ne]
        {…}<male> Varlete / varlat [Ano|Ne]
          {…+}{…} Prodělal jste toto onemocnění **v posledních 10 letech**? [Ano|Ne]
        {…}<female> Děložního čípku [Ano|Ne]
          {…+}{…} Prodělala jste toto onemocnění **v posledních 10 letech**? [Ano|Ne]
            {…+}{…} Máte v současné době toto onemocnění? [Ano|Ne]
        {…} Prsu / prsů [Ano|Ne]
          {…+}{…} Prodělala jste toto onemocnění **v posledních 10 letech**? [Ano|Ne]
            {…+}{…} Máte v současné době toto onemocnění? [Ano|Ne]
        {…} Ledviny [Ano|Ne] / ledvin [Ano|Ne]
          {…+}{…} Prodělala jste toto onemocnění **v posledních 10 letech**? [Ano|Ne]
            {…+}{…} Máte v současné době toto onemocnění? [Ano|Ne]
        {…} Močového měchýře [Ano|Ne]
          {…+}{…} Prodělala jste toto onemocnění **v posledních 10 letech**? [Ano|Ne]
            {…+}{…} Máte v současné době toto onemocnění? [Ano|Ne]
        {…} Tlustého střeva nebo konečníku (rekta) [Ano|Ne]
          {…+}{…} Prodělala jste toto onemocnění **v posledních 10 letech**? [Ano|Ne]
            {…+}{…} Máte v současné době toto onemocnění? [Ano|Ne]
        {…} Plíce [Ano|Ne] / plic [Ano|Ne]
          {…+}{…} Prodělala jste toto onemocnění **v posledních 10 letech**? [Ano|Ne]
            {…+}{…} Máte v současné době toto onemocnění? [Ano|Ne]
        {…} Kůže [Ano|Ne]
          {…+}{…} Prodělala jste toto onemocnění **v posledních 10 letech**? [Ano|Ne]
            {…+}{…} Máte v současné době toto onemocnění? [Ano|Ne]
        {…} Štítné žlázy [Ano|Ne]
          {…+}{…} Prodělala jste toto onemocnění **v posledních 10 letech**? [Ano|Ne]
            {…+}{…} Máte v současné době toto onemocnění? [Ano|Ne]
        {…} Kostí [Ano|Ne]
          {…+}{…} Prodělala jste toto onemocnění **v posledních 10 letech**? [Ano|Ne]
            {…+}{…} Máte v současné době toto onemocnění? [Ano|Ne]
        {…} Mozku [Ano|Ne]
          {…+}{…} Prodělala jste toto onemocnění **v posledních 10 letech**? [Ano|Ne]
            {…+}{…} Máte v současné době toto onemocnění? [Ano|Ne]
          {…-}{…} Byl nádor úplně odstraněn? [Ano|Ne|Nevím]
            {…+}{…} Zanechal nádor trvalé následky? (např. bolesti hlavy, změny chování a osobnosti, poruchy pohyblivosti a koordinace, zhoršení zraku, sluchu, čichu nebo řeči) [Ano|Ne]
        {…} Jiné / Ostatní [Ano|Ne]
          {…+}{…} Uveďte o jaké onemocnění se jedná: […]
    {…} Leukémie [Ano|Ne]
      {…+}{…} Prodělala jste toto onemocnění **v posledních 10 letech**? [Ano|Ne]
        {…+}{…} Máte v současné době toto onemocnění? [Ano|Ne]
    {…} Lymfom (např. Hodgkinův lymfom, Non-Hodgkinův lymfom) [Ano|Ne]
      {…+}{…} Prodělala jste toto onemocnění **v posledních 10 letech**? [Ano|Ne]
        {…+}{…} Máte v současné době toto onemocnění? [Ano|Ne]
    {…} Nezhoubný nádor mozku [Ano|Ne]
      {…+}{…} Prodělala jste toto onemocnění **v posledních 5 letech**? [Ano|Ne]
        {…+}{…} Máte v současné době toto onemocnění? [Ano|Ne]
      {…-}{…} Byl nádor úplně odstraněn? [Ano|Ne|Nevím]
        {…+}{…} Zanechal nádor trvalé následky? (např. bolesti hlavy, změny chování a osobnosti, poruchy pohyblivosti a koordinace, zhoršení zraku, sluchu, čichu nebo řeči) [Ano|Ne]

{…} 1.b) Vysoký krevní tlak a onemocnění srdce (např. srdeční infarkt, angina pectoris / bolest na hrudi / ischemická choroba srdeční, bušení srdce / arytmie, vrozená vada srdce nebo operace srdce) [Ano|Ne]
  {…+}
    {…} Vysoký krevní tlak [Ano|Ne]
      {…+} Poslední naměřená hodnota krevního tlaku:
        Systolický (vyšší hodnota) [140_mm_Hg_nebo_menší|141-160_mm_Hg|161_mm_Hg_nebo_vyšší|Nevím]
        Diastolický (nižší hodnota) [90_mm_Hg_nebo_nižší|91-100_mm_Hg|101_mm_Hg_nebo_vyšší|Nevím]
    {…} Srdeční infarkt [Ano|Ne]
      {…+}{…} Prodělal/a jste srdeční infarkt **v posledních 5 letech**? [Ano|Ne]
      {…-}{…} Prodělal/a jste srdeční infarkt **opakovaně**? [Ano|Ne]
    {…} Angina pectoris, bolest na hrudi, ischemická choroba srdeční [Ano|Ne]
    {…} Bušení srdce, arytmie [Ano|Ne]
    {…} Vrozená vada srdce [Ano|Ne]
    {…} Operace srdce [Ano|Ne]

{…} 1.c) Neurologická onemocnění (např. cévní mozková příhoda – mrtvice, epilepsie, roztroušená skleróza, Alzheimerova nemoc) [Ano|Ne]
  {…+}
    {…} Cévní mozková příhoda (mrtvice) [Ano|Ne]
      {…+}{…} Máte nějaké následky? (např. narušení schopnosti hýbat některou částí těla, porucha řeči, zhoršení zraku, epilepsie) [Ano|Ne]
    {…} Epilepsie [Ano|Ne]
      {…+}{…} Jste aktuálně veden/a v neurologické evidenci? [Ano|Ne]
        {…+}
          {…} Prodělal/a jste epileptický záchvat **v posledních 5 letech**? [Ano|Ne]
          {…} Máte nějaké psychické onemocnění? [Ano|Ne]
    {…} Roztroušená skleróza [Ano|Ne]
    {…} Alzheimerova nemoc [Ano|Ne]

{…} 1.d) Psychická onemocnění (např. úzkost, deprese, poruchy spánku, stresová porucha, poporodní deprese, syndrom vyhoření, bipolární porucha, obsedantně kompulzivní porucha, schizofrenie, autismus, Aspergerův syndrom, Downův syndrom, ADHD) [Ano|Ne]
  {…+}
    {…} Deprese, úzkost, fobie, poruchy spánku, stresová porucha, postraumatická stresová porucha [Ano|Ne]
      {…+}{…} Užíváte kombinaci tří nebo více druhů léků? [Ano|Ne]
        {…+}{…} Hospitalizovali vás, byl/a jste v pracovní neschopnosti nebo vám byla přiznána invalidita v souvislosti s tímto onemocněním? [Ano|Ne]
        {…-}
          {…} Ukončil lékař sledování nebo léčbu **před více než 2 lety**? [Ano|Ne]
          {…} Hospitalizovali vás, byl/a jste v pracovní neschopnosti nebo vám byla přiznána invalidita v souvislosti s tímto onemocněním? [Ano|Ne]
    {…}<female> Poporodní deprese [Ano|Ne]
      {…+}{…} Máte potíže nebo se s tímto onemocněním v současnosti léčíte? [Ano|Ne]
        {…-}{…} Ukončil lékař sledování nebo léčbu **před více než 6 měsíci**? [Ano|Ne]
    {…} Syndrom vyhoření [Ano|Ne]
    {…} Bipolární porucha, obsedantně kompulzivní porucha, schizofrenie [Ano|Ne]
    {…} Downův syndrom [Ano|Ne]
    {…} Autismus, porucha autistického spektra, Aspergerův syndrom [Ano|Ne]
    {…} ADHD [Ano|Ne]
      {…+}{…} Užíváte kombinaci dvou nebo více druhů léků? [Ano|Ne]
        {…-}{…} Máte potíže s pamětí, učením, udržením pozornosti či agresivním chováním? [Ano|Ne]

{…} 1.e) Onemocnění krve (např. porucha srážlivosti krve, chudokrevnost – anémie, hemofilie) [Ano|Ne]
  {…+}
    {…} Leidenská mutace nebo jiná porucha srážlivosti krve – trombofilie (např. protrombinová mutace, antitrombinová deficience, MTHFR mutace, hyperhomocytémie) [Ano|Ne]
      {…+}{…} Vyskytly se u vás komplikace jako krevní sraženiny, trombózy nebo tromboembolie? [Ano|Ne]
        {…+}{…} Byla poslední komplikace **před více než 5 lety**? [Ano|Ne]
    {…} Anemie z nedostatku železa [Ano|Ne]
    {…} Jiná anémie (např. hemoragická, aplastická, megaloblastická, hemolytická, autoimunitní hemolytická, sideroblotastická) [Ano|Ne]
    {…} Hemofilie [Ano|Ne]

{…} 1.f) Zvýšená hladinu cukru v krvi (prediabetes / porucha glukózové tolerance) nebo cukrovka (diabetes, gestační diabetes - těhotenská cukrovka) [Ano|Ne]
  {…+}
    {…} Zvýšená hladina cukru v krvi (prediabetes / porucha glukózové tolerance) [Ano|Ne]
      {…+}{…} Poslední naměřená hodnota cukru v krvi byla: [9.00_mmol/l_nebo_menší|Větší_než_9.00_mmol/l|Nevím]
    {…} Diabetes / cukrovka (diabetes mellitus 1. typu – cukrovka 1. typu, diabetes mellitus 2. typu – cukrovka 2. typu, diabetes mellitus typu LADA, diabetes mellitus typu MODY) [Ano|Ne]
      {…+}
        {…} Jak onemocnění léčíte? [Inzulínem|Pouze_léky_a/nebo_dietou]
          {…a}
            {…} Poslední naměřená hodnota cukru v krvi byla: [7.5_mmol/l_nebo_menší|Větší_než_7.5_mmol/l|Nevím]
              {…a}{…} Diagnóza byla diagnostikována: [V_posledních_5_letech|V_posledních_6_až_9_letech|Před_více_než_9_lety|Nevím]
          {…b}
            {…} Poslední naměřená hodnota cukru v krvi byla: [8.3_mmol/l_nebo_menší|Větší_než_8.3_mmol/l|Nevím]
              {…a}{…} Diagnóza byla diagnostikována: [V_posledních_6_letech|V_posledních_7_až_11_letech|Před_více_než_11_lety|Nevím]
        {…} Jsou přítomné komplikace? (např. poškození sítnice – retinopatie, poškození nervů – neuropatie, bílkoviny v moči – proteinurie, diabetické kóma v minulosti, hyperosmolární glykemický stav, infarkt myokardu, cévní mozková příhoda, amputace prstů/končetin) [Ano|Ne]
    {…}<female> Gestační diabetes (těhotenská cukrovka) [Ano|Ne]
      {…+}{…} Jste těhotná? [Ano|Ne]
        {…-}{…} Je již hodnota cukru v krvi (glykémie na lačno) normální? [Ano|Ne]
          {…-}{…} Poslední naměřená hodnota cukru v krvi byla: [9.00_mmol/l_nebo_menší|Větší_než_9.00_mmol/l|Nevím]

{…} 1.g) Onemocnění pohybového aparátu (např. bolesti zad nebo šíje, onemocnění páteře, Bechtěrevova nemoc – ankylozující spondylitida, artritida, artróza, vrozená vada pohybového aparátu) [Ano|Ne]
  {…+}
    {…} Bolest zad [Ano|Ne]
      {…+}{…} Máte v současné době toto onemocnění? [Ano|Ne]
        {…-}{…} Měl/a jste toto onemocnění opakovaně? [Ano|Ne]
          {…-}{…} Bylo poslední **před více než 2 lety**? [Ano|Ne]
    {…} Onemocnění meziobratlových plotének (např. výhřez ploténky) a meziobratlových kloubů (např. artróza, artritida) [Ano|Ne]
    {…} Bechtěrevova choroba (ankylozující spondylitida) [Ano|Ne]
      {…+}
        {…} Označte rozsah postižení: [Pouze_bolesti_a_ztuhlost_zad|Ztráta_pohyblivosti_páteře_a_bolesti_a_ztuhlost_zad]
        {…} Máte postižení ramenních nebo kyčelních kloubů a/nebo postižení dalších orgánů jako např. postižení očí, srdce či potíže s dýcháním? [Ano|Ne]
    {…} Artritida (revmatoidní, psoriatická, poúrazová, infekční nebo septická) [Ano|Ne]
      {…+}
        {…} Revmatoidní artritida [Ano|Ne]
        {…} Psoriatická artritida [Ano|Ne]
        {…} Poúrazová artritida [Ano|Ne]
          {…+} Na jakém kloubu?
            {…} Rameno [Ano|Ne] [Ano|Ne]
              {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…} Loket [Ano|Ne] [Ano|Ne]
              {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…} Zápěstí [Ano|Ne] [Ano|Ne]
              {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…} Kyčel [Ano|Ne] [Ano|Ne]
              {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…} Koleno [Ano|Ne] [Ano|Ne]
              {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…} Kotník (hlezno) [Ano|Ne] [Ano|Ne]
              {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…} Infekční nebo septická artritida [Ano|Ne]
              {…+}{…} Máte v současné době toto onemocnění? [Ano|Ne]
                {…-}{…} Zanechalo toto onemocnění deformity nebo omezení hybnosti kloubů? [Ano|Ne]
                  {…+} Na jakém kloubu?
                    {…} Rameno [Ano|Ne] [Ano|Ne]
                      {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
                    {…} Loket [Ano|Ne] [Ano|Ne]
                      {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
                    {…} Zápěstí [Ano|Ne] [Ano|Ne]
                      {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
                    {…} Kyčel [Ano|Ne] [Ano|Ne]
                      {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
                    {…} Koleno [Ano|Ne] [Ano|Ne]
                      {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
                    {…} Kotník (hlezno) [Ano|Ne] [Ano|Ne]
                      {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
    {…} Artróza nebo totální endoprotéza (TEP) [Ano|Ne]
      {…+}
        {…} Máte nebo jste měl/a artrózu? [Ano|Ne]
          {…+} Na jakém kloubu?
            {…} Rameno [Ano|Ne] [Ano|Ne]
              {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…} Loket [Ano|Ne] [Ano|Ne]
              {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…} Zápěstí [Ano|Ne] [Ano|Ne]
              {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…} Kyčel [Ano|Ne] [Ano|Ne]
              {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…} Koleno [Ano|Ne] [Ano|Ne]
              {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…} Kotník (hlezno) [Ano|Ne] [Ano|Ne]
              {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
        {…} Máte provedenou náhradu kloubu (totální endoprotéza, TEP), uvažujete o ní nebo vám byla doporučena? [Ano|Ne]
          {…+} Na jakém kloubu?
            {…} Rameno [Ano|Ne] [Ano|Ne]
              {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…} Loket [Ano|Ne] [Ano|Ne]
              {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…} Zápěstí [Ano|Ne] [Ano|Ne]
              {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…} Kyčel [Ano|Ne] [Ano|Ne]
              {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…} Koleno [Ano|Ne] [Ano|Ne]
              {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…} Kotník (hlezno) [Ano|Ne] [Ano|Ne]
              {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
    {…} Vrozená vada pohybového aparátu [Ano|Ne]
      {…+}{…} Uveďte diagnózu: […]

{…} 1.h) Nic z výše uvedeného [ano|ne]

### {D} Onemocnění - část 2
#### 2. Máte nebo jste měl/a **v posledních 7 letech** některé z následujících onemocnění, kvůli kterým vás lékař vyšetřoval, sledoval nebo léčil?

{…} 2.a) Porucha látkové přeměny (např. zvýšený cholesterol, zvýšené jaterní testy, dna) [Ano|Ne]
  {…+}
    {…} Zvýšený cholesterol [Ano|Ne]
      {…+}{…} Poslední naměřená hodnota cholesterolu: [7.1_mmol/l_nebo_menší|7,1–9_mmol/l|9,1_mmol/l_nebo_větší|Nevím]
    {…} Zvýšené jaterní testy [Ano|Ne]
    {…} Dna [Ano|Ne]
      {…+}
        {…} Užíváte pro toto onemocnění léky? [Ano|Ne]
        {…} Hospitalizovali vás, nebo jste byl/a v pracovní neshopnosti kvůli dně, dnavé artritidě, hyperurikémii nebo uratické artritidě? [Ano|Ne]

{…} 2.b) Onemocnění dýchací soustavy (např. astma, chronická obstrukční plicní nemoc - CHOPN, bronchitida, plicní fibróza, zápal plic, zánět průdušek, alergie) [Ano|Ne]
  {…+}
    {…} Astma [Ano|Ne]
      {…+}{…} Jak často užíváte léky v souvislosti s tímto onemocněním? [Pouze_při_obtížích_nebo_sezónně|Pravidelně|Léky_neužívám]
        {…b}{…} Hospitalizovali vás anebo jste byl/a **v posledních 2 letech** v pracovní neschopnosti v souvislosti s tímto onemocněním? [Ano|Ne]
    {…} Chronická obstrukční plicní nemoc (CHOPN), chronická bronchitida, plicní fibróza [Ano|Ne]
    {…} Zápal plic, akutní bronchitida, zánět průdušek [Ano|Ne]
      {…+}{…} Máte v současnosti toto onemocnění? [Ano|Ne]
    {…} Alergie [Ano|Ne]
      {…+}{…} Hospitalizovali vás anebo jste byl/a **v posledních 2 letech** v pracovní neschopnosti v souvislosti s tímto onemocněním? [Ano|Ne]

{…} 2.c) Onemocnění trávící soustavy (např. žlučníkové kameny, vřed dvanáctníku, žaludeční vřed, reflux jícnu, zánět slinivky břišní – pankreatitida, onemocnění jater, Crohnova nemoc, ulcerózní kolitida, celiakie, onemocnění nebo vrozené vady jícnu, žaludku nebo střev) [Ano|Ne]
  {…+}
    {…} Žlučníkové kameny [Ano|Ne]
      {…+}{…} Máte v současnosti toto onemocnění? [Ano|Ne]
        {…-}{…} Operovali vás v souvislosti s tímto onemocněním? [Ano|Ne]
          {…-}{…} Opakovalo se u vás toto onemocnění? [Ano|Ne]
    {…} Vřed dvanáctníku (duodenum), žaludeční vřed [Ano|Ne]
      {…+}{…} Máte v současnosti toto onemocnění? [Ano|Ne]
        {…-}{…} Operovali vás v souvislosti s tímto onemocněním? [Ano|Ne]
          {…-}{…} Opakovalo se u vás toto onemocnění? [Ano|Ne]
    {…} Reflux jícnu (gastrozofagiální reflux) [Ano|Ne]
      {…+}{…} Máte nebo měl/a jste komplikace? (např.potíže s polykáním, zvracení krve, vřed nebo zúžení jícnu, Barretův jícen, brániční / jícnová kýla – hiátová hernie) [Ano|Ne]
    {…} Zánět slinivky břišní (pankreatitida) [Ano|Ne]
      {…+}{…} Akutní zánět slinivky břišní [Ano|Ne]
        {…+}{…} Měl jste 3 a více záchvatů **za posledních 7 let**? [Ano|Ne]
          {…-}{…} Byl poslední záchvat **před více než 2 lety**? [Ano|Ne]
      {…+}{…} Chronický zánět slinivky břišní [Ano|Ne]
    {…} Onemocnění jater (např. cirhóza, fibróza nebo ztučnění jater – steatóza, cysta na játrech, hemangiom jater) [Ano|Ne]
    {…} Crohnova nemoc, ulcerózní kolitida [Ano|Ne]
    {…} Celiakie [Ano|Ne]
      {…+}{…} Máte komplikace v souvislosti s tímto onemocněním? (např. nízka váha, podvýživa, malabsorpční syndrom) [Ano|Ne]
    {…} Vrozená vada jícnu, žaludku nebo střev [Ano|Ne]

{…} 2.d) Onemocnění močového ústrojí (např. ledvinové kameny, zánět ledvin, močového měchýře nebo močových cest, vrozená vada ledvin, močového měchýře nebo močových cest) [Ano|Ne]
  {…+}
    {…} Ledvinové kameny [Ano|Ne]
      {…+}{…} Máte v současnosti toto onemocnění? [Ano|Ne]
        {…-}{…} Operovali vás v souvislosti s tímto onemocněním? [Ano|Ne]
          {…-}{…} Opakovalo se u vás toto onemocnění? [Ano|Ne]
    {…} Vrozená vada ledvin, močového měchýře, močových cest [Ano|Ne]
    {…} Zánět močového měchýře [Ano|Ne]
      {…+}{…} Máte v současnosti toto onemocnění? [Ano|Ne]
        {…-}{…} Opakovalo se u vás toto onemocnění? [Ano|Ne]
    {…} Zánět močových cest [Ano|Ne]
      {…+}{…} Máte v současnosti toto onemocnění? [Ano|Ne]
        {…-}{…} Opakovalo se u vás toto onemocnění? [Ano|Ne]
    {…} Zánět ledvin [Ano|Ne]
      {…+}{…} Máte v současnosti toto onemocnění? [Ano|Ne]
        {…-}{…} Opakovalo se u vás toto onemocnění? [Ano|Ne]

{…}<female> 2.e) Gynekologická onemocnění a onemocnění prsou (např. cysty na vaječnících, endometrióza, děložní myomy, dysplazie děložního čípku / pozitivní nález ve stěru z děložního čípku, bulka v prsu) [Ano|Ne]
  {…+}
    {…} Cysta na vaječníku [Ano|Ne]
    {…} Polycystické vaječníky [Ano|Ne]
    {…} Endometrióza [Ano|Ne]
    {…} Děložní myomy [Ano|Ne]
    {…} Dysplazie děložního čípku (pozitivní nález ve stěru z děložního čípku CIN I., CIN II., CIN III., karcinom in situ) [Ano|Ne]
      {…+} Jaký byl výsledek nálezu? [CIN_I_(lehké_dysplastické_změny)|CIN_II_(středně_těžké_dysplastické_změny)|CIN_III_(těžké_dysplastické_změny)|Karcinom_in_situ|Nevím]
    {…} Bulka v prsu, pozitivní nález na mamografu [Ano|Ne]

    



{…}<male> 2.f) Onemocnění prostaty a onemocnění prsou (např. zvětšení prostaty, bulka v prsu) [Ano|Ne]
  {…+}




{…} 2.g) Infekční nemoci (např. žloutenka – hepatitida – typu A, B, C, D, E, mononukleóza, Lymeská borelióza, encefalitida, meningitida, HIV) [Ano|Ne]
  {…+}
    {…} Žloutenka (hepatitida) typu A nebo E [Ano|Ne]
      {…+}{…} Máte v současné době toto onemocnění? [Ano|Ne]
    {…} Žloutenka (hepatitida) typu B nebo D [Ano|Ne]
    {…} Žloutenka (hepatitida) typu C [Ano|Ne]
    {…} Infekční mononukleóza [Ano|Ne]
      {…+}{…} Máte v současné době toto onemocnění? [Ano|Ne]
    {…} Lymeská borelióza [Ano|Ne]
      {…+}{…} Máte v současné době toto onemocnění? [Ano|Ne]
        {…-}{…} Zanechalo toto onemocnění trvalé následky? (např. únava, deprese, neurologické komplikace, postižení srdce) [Ano|Ne]
    {…} Encefalitida (včetně klíšťové) [Ano|Ne]
      {…+}{…} Máte v současné době toto onemocnění? [Ano|Ne]
        {…-}{…} Zanechalo toto onemocnění trvalé následky? (např. neurologické komplikace, epilepsie, ochrnutí, bolesti hlavy, poruchy soustředění nebo nálad) [Ano|Ne]
    {…} Meningitida [Ano|Ne]
      {…+}{…} Máte v současné době toto onemocnění? [Ano|Ne]
        {…-}{…} Zanechalo toto onemocnění trvalé následky? (např. neurologické komplikace, epilepsie, ochrnutí, bolesti hlavy, poruchy soustředění nebo nálad) [Ano|Ne]
    {…} HIV [Ano|Ne]

{…} 2.h) Onemocnění štítné žlázy (např. snížená funkce, zvýšená funkce, cysta nebo uzly) [Ano|Ne]
  {…+}
    {…} Snížená funkce štítné žlázy (hypofunkce) [Ano|Ne]
    {…} Zvýšená funkce štítné žlázy (hyperfunkce) [Ano|Ne]
    {…} Cysta nebo uzly štítné žlázy [Ano|Ne]

{…} 2.i) Onemocnění kůže (např. lupénka, atopický ekzém, ekzém) [Ano|Ne]
  {…+}
    {…} Lupénka (psoriáza) [Ano|Ne]
      {…+}{…} Měla/a jste někdy bolest či otok kloubů, bolestivý a oteklý celý prst, bolest paty a/nebo se Vám dělají dolíčky na nehtech? [Ano|Ne]
    {…} Atopický ekzém (atopická dermatitida) [Ano|Ne]
    {…} Ekzém (kontaktní dermatitida) [Ano|Ne]
      {…+}{…} Máte rozsáhlé oblasti suché kůže, časté svědění, zarudnutí, oděrky, mokvání či popraskání pokožky? [Ano|Ne]

{…} 2.j) Onemocnění zrakového ústrojí (např. krátkozrakost, dalekozrakost víc jak 10 dioptrií, astigmatizmus, tupozrakost, šilhavost, keratokonus, zelený zákal, šedý zákal, slepota) [Ano|Ne]
  {…+}
    {…} Krátkozrakost nebo dalekozrakost více než 10 dioptrií [Ano|Ne]
    {…} Astigmatismus [Ano|Ne]
    {…} Tupozrakost [Ano|Ne]
    {…} Šilhavost [Ano|Ne]
    {…} Keratokonus [Ano|Ne]
    {…} Zelený zákal (glaukom, zvýšený nitrooční tlak, NOT) [Ano|Ne]
    {…} Šedý zákal (katarakta) [Ano|Ne]
    {…} Slepota (např. slepota 1 oka, částečná nebo praktická, úplná) [Ano|Ne]
      {…+}
        {…} Slepota 1 oka [Ano|Ne]
          {…+}{…} Oko: [Pravé|Levé|Pravé+Levé]
        {…} Částečná nebo praktická slepota [Ano|Ne]
        {…} Úplná slepota [Ano|Ne]

{…} 2.k) Onemocnění sluchového ústrojí (např. pískání nebo šum v uchu – tinnitus, nedoslýchavost, hluchota) [Ano|Ne]
  {…+}
    {…} Pískání nebo šum v uchu (tinnitus) [Ano|Ne]
      {…+}{…} Máte problémy nebo se léčíte v současnosti s tímto onemocněním? [Ano|Ne]
        {…+}{…} Máte sníženou slyšitelnost jednoho nebo obou uší? [Ano|Ne]
    {…} Nedoslýchavost 1 ucha [Ano|Ne]
    {…} Hluchota 1 ucha [Ano|Ne]
    {…} Nedoslýchavost nebo částečná hluchota obou uší [Ano|Ne]
    {…} Ztráta sluchu (úplná hluchota obou uší) [Ano|Ne]

{…} 2.l) Nic z výše uvedeného [Ano|Ne]

### {E} Onemocnění - část 3
{…} 3.a) Máte v současné době zdravotní obtíže? (nemoc, pracovní neschopnost, plánujete navštívit lékaře, probíhá u vás vyšetřování, čekáte na výsledky testů, zahájení léčby či operaci) [Ano|Ne]
  {…+}
    {…} Jsem v pracovní neschopnosti nebo nejsem schopen práce (v případě OSVČ) [Ano|Ne]
      {…+}{…} Uveďte důvod: […]
    {…} Mám potíže, pro které plánuji vyhledat lékaře [Ano|Ne]
      {…+}{…} Uveďte důvod: […]
    {…} Probíhá u mě vyšetřování, testy nebo čekám na výsledky provedených vyšetření [Ano|Ne]
      {…+}{…} Uveďte důvod: […]
    {…} Čekám na zahájení jakékoliv formy léčby nebo operaci [Ano|Ne]
      {…+}
        {…} Léčba (kromě operace) [Ano|Ne]
          {…+}{…} Uveďte důvod: […]
        {…} Operace [Ano|Ne]
          {…+}{…} Vyberte plánované operace (ze seznamu): […]
```md
Operace mozku
Operace míchy
Operace meziobratlových plotének
Operace skoliózy páteře
Operace páteře
Laserová operace pravého oka
Laserová operace levého oka
Operace pravého oka
Operace levého oka
Operace šedého zákalu pravého oka
Operace šedého zákalu levého oka
Operace zeleného zákalu
Operace ušního bubínku pravého ucha
Operace ušního bubínku levého ucha
Operace pravého ucha
Operace levého ucha
Operace středního ucha
Operace sluchového ústrojí
Operace nosní přepážky
Operace nebo odstranění nosních mandlí
Operace nosní dutiny a/nebo nebo přínosových dutin
Operace čelisti
Operace rozštěpu patra
Operace nebo odstranění krčních mandlí
Operace slinných žláz
Operace zubů v celkové anestézii
Operace hlasivek
Operace štítné žlázy
Operace srdce a/ nebo aorty
Operace břišní aorty
Operace krčních tepen
Operace plic
Operace hrudní stěny
Operace hemoroidů
Operace křečových žil (varixů)
Operace žil a/nebo tepen
Operace jícnu
Operace refluxu
Operace žaludku
Operace slinivky břišní (pankreasu)
Operace jater
Operace sleziny
Operace střev
Operace slepého střeva (apendixu)
Operace konečníku
Operace ledvin
Operace močového měchýře
Operace močových cest
Operace močové trubice
Operace prsou
Operace nebo odstranění dělohy
Operace, odstranění nebo zákrok na děložním čípku
Operace nebo odstranění vaječníků
Operace, odstranění nebo zákrok na vejcovodech
Operace nebo odstranění varlat/e
Operace prostaty
Operace pravé horní končetiny
Operace levé horní končetiny
Operace pravého ramenního kloubu
Operace levého ramenního kloubu
Operace pravého loketního kloubu
Operace levého loketního kloubu
Operace pravého zápěstí
Operace levého zápěstí
Operace pravé ruky (od zápěstí po konečky prstů)
Operace levé ruky (od zápěstí po konečky prstů)
Operace karpálních tunelů
Operace pravého kyčelního kloubu
Operace levého kyčelního kloubu
Operace pravého kolenního kloubu
Operace levého kolenního kloubu
Operace pravého hlezenního kloubu
Operace levého hlezenního kloubu
Operace pravé dolní končetiny
Operace levé dolní končetiny
Operace pravé nohy (od kotníku po konečky prstů)
Operace levé nohy (od kotníku po konečky prstů)
Operace vbočeného palce nohy (haluxu)
Operace patních ostruh
Odstranění nádoru kůže
Operace tukových výrustků (v lokální anestezii)
Operace břišní kýly
Operace pupeční kýly
Operace tříselné kýly
Operace kýly
Operace žlučníku
Jiná operace
```

{…} 3.b) Máte nebo jste měl/a přiznanou invaliditu 1., 2., 3. stupně a /nebo sníženou soběstačnost? Jste nebo jste byl/a osobou se zdravotním zněvýhodněním (např. držitel průkazu ZTP, OZZ)? Žádal/a jste o jejich přiznání? [Ano|Ne]
  {…+}
    {…} Osoba se zdravotním znevýhodněním (např. držitel průkazu ZTP nebo OZZ) [Ano|Ne]
      {…+}
        {…} V jaké fázi aktuálně je žádost? [Podaná|Přiznaná|Ukončená|Zamítnutá]
        {…} Uveďte měsíc a rok (MM/RRRR) - podání / přiznání / ukončení / zamítnutí: […]
        {…} Pro jakou diagnózu, případně jaké diagnózy? […]
    {…} Invalidita [Ano|Ne]
      {…+}
        {…} V jaké fázi aktuálně je žádost? [Podaná|Přiznaná|Ukončená|Zamítnutá]
          {…bc}{…} Uveďte stupeň snížené soběstačnosti (závislosti): [1|2|3|4]
        {…} Uveďte měsíc a rok (MM/RRRR) - podání / přiznání / ukončení / zamítnutí: […]
        {…} Pro jakou diagnózu, případně jaké diagnózy? […]
    {…} Snížená soběstačnost [Ano|Ne]
        {…} V jaké fázi aktuálně je žádost? [Podaná|Přiznaná|Ukončená|Zamítnutá]
          {…bc}{…} Uveďte stupeň invalidity: [1|2|3]
        {…} Uveďte měsíc a rok (MM/RRRR) - podání / přiznání / ukončení / zamítnutí: […]
        {…} Pro jakou diagnózu, případně jaké diagnózy? […]

{…} 3.c) Máte nebo jste měl/a nějaké jiné onemocnění nebo potíže (mimo úrazy), které jste neuvedl v tomto dotazníku a pro které vás vyšetřoval, sledoval nebo léčil lékař? [Ano|Ne]
  {…+}
    Vyberte onemocnění nebo potíže ze seznamu: […]
```md
Jiné onemocnění nebo potíž
Artróza prstů
Artritida prstů
Alergická rýma (polinóza, "senná rýma")
Chřipka
Nosní polypy
Odstranění nosních nebo krčních mandlí
Operace nosní přepážky
Poúrazový pneumothorax
Zánět hrtanu (laryngitida)
Zánět mandlí (tonsilitida, "angína")
Zánět plic (pneumonie)
Neštovice
Pásový opar (herpes zoster)
Příušnice
Salmonelóza
Spála
Spalničky
Stafylokoková infekce
Streptokoková infekce
Střevní infekce
Zarděnky
Odstranění bradavic
Inkontinence moči
Prostá cysta
Migréna
Neuralgie trojklaného nervu (bolest trojklaného nervu)
Obrna lícního nervu
Sydrom karpálního tunelu (po provedení operace)
Hemoroidy
Hypotenze (nízký krevní tlak)
Křečové žíly šourku (varikokéla)
Křečové žíly (varixy)
Zánět povrchových žil (tromboflebitida)
Operativní odstranění oční vady (korekce dioptrií)
Zánět spojivek (konjuktivitida)
Zánět sítnice
Císařský řez
Fibroadenom prsu
Kapavka (syfilis)
Těhotenství, porod
Torze vaječníku (otočení vaječníku)
Torze varlete (otočení varlete)
Zánět Bartoliniho žlázy
Zánět pochvy
Zvětšení nebo zmenšení prsou
Ganglion
Tenisový loket, oštěpařský loket, golfový loket
Vbočený palec (hallux valgus)
Zruhlý palec (hallux rigidus)
Zánět Achillovy šlachy
Patní ostruhy (calcar calcanei)
Osteoporóza (bez zlomenin)
Osteoporóza (se zlomeninami)
Platfus (plochá noha)
Skolióza páteře
Akutní zánět žaludku (gastritida)
Kýla (pupeční, břišní, tříselná, brániční)
Neprůchodnost střev (ileus)
Odstranění slepého střeva (apendektomie)
Odstranění sleziny (splenektomie)
Odstranění žlučníku (cholecystektomie)
Onemocnění zubů nebo dásní
Reflux jícnu
Překyselení žaludku (léčba např. Helicid, Omeprazol)
Střevní viróza
Zánět slepého střeva (apendicitida)
Zánět středního ucha (otitis media)
Zánět nebo ucpání zvukovodu
Gilbertův syndrom
Struma (zvětšení štítné žlázy)
Spánková apnoe
Onemocnění lymfatických uzlin (kromě rakoviny)
Cysta v mozku (např. arachnoidální cysta, pineální cysta)
Kožní mykóza
Kožní bradavice, fibromy, papilomy
Porucha příjmu potravy (anorexie, bulimie)
Fistule (perianální píštěl)
Podstoupená operace pravé horní končetiny
Podstoupená operace levé horní končetiny
Podstoupená operace pravého ramenního kloubu
Podstoupená operace levého ramenního kloubu
Podstoupená operace pravého loketního kloubu
Podstoupená operace levého loketního kloubu
Podstoupená operace pravého zápěstí
Podstoupená operace levého zápěstí
Podstoupená operace pravé ruky (od zápěstí po konečky prstů)
Podstoupená operace levé ruky (od zápěstí po konečky prstů)
Podstoupená operace karpálních tunelů
Podstoupená operace pravého kyčelního kloubu
Podstoupená operace levého kyčelního kloubu
Podstoupená operace pravého kolenního kloubu
Podstoupená operace levého kolenního kloubu
Podstoupená operace pravého hlezenního kloubu
Podstoupená operace levého hlezenního kloubu
Podstoupená operace pravé dolní končetiny
Podstoupená operace levé dolní končetiny
Podstoupená operace pravé nohy (od kotníku po konečky prstů)
Podstoupená operace levé nohy (od kotníku po konečky prstů)
Podstoupená operace mozku
Podstoupená operace míchy
Podstoupená operace meziobratlových plotének
Podstoupená operace páteře
Podstoupená laserová operace pravého oka
Podstoupená laserová operace levého oka
Podstoupená operace pravého oka
Podstoupená operace levého oka
Podstoupená operace šedého zákalu pravého oka
Podstoupená operace šedého zákalu levého oka
Podstoupená operace zeleného zákalu
Podstoupená operace ušního bubínku pravého ucha
Podstoupená operace ušního bubínku levého ucha
Podstoupená operace pravého ucha
Podstoupená operace levého ucha
Podstoupená operace středního ucha
Podstoupená operace sluchového ústrojí
Podstoupená operace nosní přepážky
Podstoupená operace nebo odstranění nosních mandlí
Podstoupená operace nosní dutiny a/nebo přínosových dutin
Podstoupená operace čelisti
Podstoupená operace rozštěpu patra
Podstoupená operace nebo odstranění krčních mandlí
Podstoupená operace zubů v celkové anestézii
Podstoupená operace hlasivek
Podstoupená operace štítné žlázy
Podstoupená operace plic (kromě transplantace)
Podstoupená operace hemoroidů
Podstoupená operace křečových žil (varixů)
Podstoupená operace jícnu
Podstoupená operace žaludku
Podstoupená operace slinivky břišní (pankreasu)
Podstoupená operace jater (kromě transplantace)
Podstoupená operace střev
Podstoupená operace konečníku
Podstoupená operace ledvin (kromě transplantace)
Podstoupená operace močového měchýře
Podstoupená operace močových cest
Podstoupená operace dělohy (hysterektomie)
Podstoupená operace, odstranění nebo zákrok na děložním čípku
Podstoupená operace vaječníků
Podstoupená operace vejcovodů
Podstoupená operace nebo odstranění varlat/e
Podstoupená operace prostaty
Podstoupená operace tukových výrustků (v lokální anestezii)
Podstoupená operace břišní kýly
Podstoupená operace pupeční kýly
Podstoupená operace tříselné kýly
Podstoupená operace kýly
Transplantace orgánů (např. srdce, plíce, játra, ledviny)
Transplantace kostní dřeně
Rakovina
Rakovina prostaty
Rakovina varlete / varlat
Rakovina děložního čípku
Rakovina prsu / prsů
Rakovina ledviny / ledvin
Rakovina močového měchýře
Rakovina tlustého střeva nebo konečníku (rekta)
Rakovina plíce / plic
Rakovina kůže
Rakovina štítné žlázy
Rakovina kostí
Rakovina mozku
Rakovina jiná / ostatní
Leukémie
Lymfom
Hodgkinův lymfom
Non-Hodgkinův lymfom
Nezhoubný nádor mozku
Hypertenze (vysoký krevní tlak)
Srdeční infarkt
Infarkt myokardu
Angina pectoris
Bolest na hrudi
Bušení srdce
Srdeční arytmie
Vrozená vada srdce
Operace srdce
Cévní mozková příhoda
CMP
Mozková mrtvice
Epilepsie
Roztroušená skleróza
Alzheimerova nemoc
Deprese
Úzkost
Fobie
Poruchy spánku
Stresová porucha
Posttraumatická stresová porucha
Poporodní deprese
Syndrom vyhoření
Bipolární porucha
Obsedantně kompulzivní porucha
Schizofrenie
Downův syndrom
Autismus
Porucha autistického spektra
ADHD
Leidenská mutace
Porucha srážlivosti krve
Trombofilie
Protrombinová mutace
Antitrombinová mutace
MTHFR mutace
Hyperhomocytémie
Anemie z nedostatku železa
Hemoragická anemie
Megaloblastická anemie
Hemolytická anemie
Autoimunitní hemolytická anemie
Sideroblotastická anemie
Hemofilie
Zvýšená hladina cukru v krvi
Prediabetes
Porucha glukózové tolerance
Diabetes mellitus 1. typu
Cukrovka 1. typu
Diabetes mellitus typu LADA
Diabetes mellitus 2. typu
Cukrovka 2. typu
Diabetes mellitus typu MODY
Gestační diabetes
Těhotenská cukrovka
Výhřez ploténky
Onemocnění meziobratlových plotének
Onemocnění meziobratlových kloubů
Bolest zad
Bechtěrevova choroba
Ankylozující spondylitida
Artritida
Revmatoidní artritida
Psoriatická artritida
Poúrazová artritida
Infekční artritida
Septická artritida
Artróza
Totální endoprotéza
Zvýšený cholesterol
Zvýšené jaterní testy
Dna
Astma
Chronická obstrukční plicní nemoc (CHOPN)
Chronická bronchitida
Plicní fibróza
Zápal plic
Akutní bronchitida
Zánět průdušek
Alergie
Žlučníkové kameny
Vřed dvanáctníku (duodenum)
Vřed dvanácterníku (duodenum)
Žaludeční vřed
Reflux jícnu (gastrozofagiální reflux)
Zánět slinivky břišní (pankreatitida)
Akutní zánět slinivky břišní
Chronický zánět slinivky břišní
Onemocnění jater
Cirhóza jater
Fibróza jater
Ztučnění (steatóza) jater
Cysta na játrech
Hemangiom jater
Crohnova nemoc
Ulcerózní kolitida
Celiakie
Vrozená vada jícnu
Vrozená vada žaludku
Vrozená vada střev
Ledvinové kameny
Vrozená vada ledvin
Vrozená vada močového měchýře
Vrozená vada močových cest
Zánět močového měchýře
Zánět močových cest
Zánět ledvin
Cysta na vaječníku
Polycystické vaječníky
Endometrióza
Děložní myomy
Pozitivní nález ve stěru z děložního čípku
Dysplazie děložního čípku
Bulka v prsu (ženy)
Pozitivní nález na mamografu
Mutace v genech BRCA1 a/nebo BRCA2 (ženy)
Zvětšená prostata
Bulka v prsu (muži)
Mutace v genech BRCA1 a/nebo BRCA2 (muži)
Žloutenka (hepatitida) typu A
Žloutenka (hepatitida) typu E
Žloutenka (hepatitida) typu B
Žloutenka (hepatitida) typu D
Žloutenka (hepatitida) typu C
Infekční mononukleóza
Lymeská borelióza
Encefalitida
Klíšťová encefalitida
Meningitida
HIV
Snížená funkce štítné žlázy (hypofunkce)
Zvýšená funkce štítné žlázy (hyperfuknce)
Cysta nebo uzly štítné žlázy
Lupénka (psoriáza)
Atopický ekzém (atopická dermatitida)
Ekzém (kontaktní dermatitida)
Krátkozrakost (více než 10 dioptrií)
Dalekozrakost (více než 10 dioptrií)
Astigmatismus
Tupozrakost
Šilhavost
Keratokonus
Zelený zákal (glaukom)
Šedý zákal (katarakta)
Slepota (1 oka, částečná nebo praktická, úplná)
Pískání nebo šum v uchu (tinnitus)
Nedoslýchavost 1 ucha
Hluchota 1 ucha
Částečná hluchota obou uší
Ztráta sluchu (úplná hluchota)
```

### {F} Trvalé následky
#### 4. Měl/a jste v minulosti úraz, který zanechal trvalé následky? (např. poškození kloubů, omezení hybnosti, ochrnutí, ztráta končetin nebo orgánu, pakloub, ztráta zraku nebo sluchu apod.)
Na jaké části těla máte trvalý následek? Uveďte všechny trvalé následky.

{…} Hlava [Ano|Ne]
  {…+} Na jaké části hlavy máte trvalý následek?
    {…} Nos, ústa, krk [Ano|Ne]
      {…+} Jaký máte trvalý následek?
        {…} Ztráta nosu nebo čichu [Ano|Ne]
        {…} Ztráta jazyka [Ano|Ne]
        {…} Ztráta zubu/zubů [Ano|Ne]
        {…} Ztráta hlasu nebo poškození hlasivek [Ano|Ne]
        {…} Trvalá tracheostomie [Ano|Ne]
        {…} Jizvy (např. vzniklé poraněním nebo popálením) [Ano|Ne]
        {…} Jiný trvalý následek [Ano|Ne]
          {…+}{…} Uveď: […]
    {…} Oko, ucho [Ano|Ne]
      {…+} Jaký máte trvalý následek?
        {…} Ztráta oka nebo slepota jednoho oka [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
        {…} Ztráta zraku (úplná slepota) [Ano|Ne]
        {…} Částečná ztráta zraku (částečná slepota, praktická slepota) [Ano|Ne]
        {…} Pískání nebo šum v uchu (tinnitus) [Ano|Ne]
        {…} Ztráta ucha nebo poškození boltce [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
        {…} Nedoslýchavost jednoho ucha [Ano|Ne]
        {…} Hluchota jednoho ucha [Ano|Ne]
        {…} Nedoslýchavost nebo částečná hluchota obou uší [Ano|Ne]
        {…} Ztráta sluchu (úplná hluchota obou uší) [Ano|Ne]
        {…} Jiný trvalý následek [Ano|Ne]
          {…+}{…} Uveď: […]
    {…} Jiný trvalý následek [Ano|Ne]
      {…+}{…} Uveď: […]

{…} Páteř [Ano|Ne]
  {…+} Jaký máte trvalý následek?
    {…} Omezení hybnosti [Ano|Ne]
    {…} Poškození páteře, míchy [Ano|Ne]

{…} Trvalé následky trupu a orgánů [Ano|Ne]
  {…+} Jaký máte trvalý následek?
    {…} Ztráta části nebo celé plíce [Ano|Ne]
      {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
    {…} Poškození funkce plic nebo srůsty plic [Ano|Ne]
      {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
    {…} Ztráta prsu [Ano|Ne]
      {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
    {…} Zúžení jícnu [Ano|Ne]
    {…} Ztráta sleziny nebo její části [Ano|Ne]
    {…} Ztráta části jater [Ano|Ne]
    {…} Ztráta jedné ledviny nebo její části [Ano|Ne]
      {…+}{…} Na jaké straně? [Pravá|Levá]
        {…ab}{…} Druhá ledvina je plně funkční [Ano|Ne]
    {…} Ztráta obou ledvin [Ano|Ne]
    {…} Porušení funkce trávících orgánů [Ano|Ne]
    {…} Jizvy (např. vzniklé poraněním nebo popálením) [Ano|Ne]
    {…} Jiný trvalý následek [Ano|Ne]
      {…+}{…} Uveď: […]

{…} Horní končetina [Ano|Ne] [Ano|Ne]
  {…+} Jaký máte trvalý následek?
    {…} Omezení hybnosti, viklavost nebo nestabilita kloubu a/nebo pakloub [Ano|Ne]
      {…+} Na jakém kloubu máte trvalý následek?
        {…} Rameno [Ano|Ne] [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
        {…} Loket [Ano|Ne] [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
        {…} Zápěstí [Ano|Ne] [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
        {…} Prsty [Ano|Ne] [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
        {…} Jiný trvalý následek [Ano|Ne]
          {…+}{…} Uveď: […]
    {…} Ztráta prstu nebo horní končetiny [Ano|Ne]
      {…+} Jaký máte trvalý následek?
        {…} Ztráta prstu [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
        {…} Ztráta horní končetiny v úrovni předloktí [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
        {…} Ztráta horní končetiny v úrovni pažní kosti [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
        {…} Ztráta horní končetiny v zápěstí [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
        {…} Jiný trvalý následek [Ano|Ne]
          {…+}{…} Uveď: […]
    {…} Trvalé neurologické příznaky (parestézie, brnění, ochrnutí apod.) [Ano|Ne]
    {…} Jizvy (např. vzniklé poraněním nebo popálením) [Ano|Ne]
    {…} Jiný trvalý následek [Ano|Ne]
      {…+}{…} Uveď: […]

{…} Dolní končetina [Ano|Ne] [Ano|Ne]
  {…+} Jaký máte trvalý následek?
    {…} Omezení hybnosti, viklavost nebo nestabilita kloubu a/nebo pakloub [Ano|Ne]
      {…+} Na jakém kloubu máte trvalý následek?
        {…} Kyčel [Ano|Ne] [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
        {…} Koleno [Ano|Ne] [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
        {…} Kotník (hlezno) [Ano|Ne] [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
        {…} Jiný trvalý následek [Ano|Ne]
          {…+}{…} Uveď: […]
    {…} Ztráta prstu nebo dolní končetiny [Ano|Ne]
      {…+} Jaký máte trvalý následek?
        {…} Ztráta prstu [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
        {…} Ztráta v úrovni stehna [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
        {…} Ztráta v úrovni bérce [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
        {…} Ztráta v hlezenním kloubu (kotníku) [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
        {…} Jiný trvalý následek [Ano|Ne]
          {…+}{…} Uveď: […]
    {…} Zkrácení končetiny o 3 cm nebo více [Ano|Ne]
      {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
    {…} Trvalé neurologické příznaky (parestézie, brnění, ochrnutí apod.) [Ano|Ne]
    {…} Jizvy (např. vzniklé poraněním nebo popálením) [Ano|Ne]
    {…} Jiný trvalý následek [Ano|Ne]
      {…+}{…} Uveď: […]
{…} Nic z výše uvedeného [Ano|Ne] [Ano|Ne]

### {G} Úraz
#### 5. Měl/a jste **v posledních 7 letech** úraz? (např. zlomenina, podvrtnutí, vykloubení, poranění vazů a šlach, popálení, otřes mozku apod.)
Jaká část těla byla poraněna? Uveďte všechna poranění.
    
{…} Hlava [Ano|Ne]
  {…+} O jaký úraz se jednalo?
    {…} Zlomenina [Ano|Ne] [Ano|Ne]
      {…+} Jaká část hlavy byla poraněna?
        {…} Kosti lebky [Ano|Ne]
          {…+}{…} Kolikrát? […]
        {…} Nos [Ano|Ne]
          {…+}{…} Kolikrát? […]
        {…} Čelist [Ano|Ne]
          {…+}{…} Kolikrát? […]
    {…} Podvrtnutí čelisti [Ano|Ne]
      {…+}{…} Kolikrát? […]
    {…} Vykloubení, vymknutí (luxace) čelisti [Ano|Ne]
      {…+}{…} Kolikrát? […]
    {…} Pohmoždění (kontuze) [Ano|Ne] v oblasti hlavy [Ano|Ne]
      {…+} Jaká část hlavy byla poraněna?
        {…} Mozek [Ano|Ne]
          {…+}{…} Kolikrát? […]
        {…} Oko [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…ac}{…} Napravo kolikrát? […]
            {…bc}{…} Nalevo kolikrát? […]
        {…} Nos [Ano|Ne]
          {…+}{…} Kolikrát? […]
        {…} Čelist [Ano|Ne]
          {…+}{…} Kolikrát? […]
        {…} Jiná část hlavy [Ano|Ne]
          {…+}
            {…} Uveď popis: […]
            {…} Kolikrát? […]
    {…} Poleptání, popálení, otevřená nebo tržná rána [Ano|Ne]
      {…+}{…} Kolikrát? […]
    {…} Otřes mozku [Ano|Ne]
      {…+}{…} Kolikrát? […]
    {…} Jiný úraz [Ano|Ne]
      {…+}
        {…} Uveď popis: […]
        {…} Kolikrát? […]

{…} Páteř a záda [Ano|Ne]
  {…+} O jaký úraz se jednalo?
    {…} Zlomenina [Ano|Ne]
      {…+} Jaká část páteře byla poraněna?
        {…} Krční obratle [Ano|Ne]
          {…+}{…} Kolikrát? […]
        {…} Hrudní obratle [Ano|Ne]
          {…+}{…} Kolikrát? […]
        {…} Bederní a/nebo křížové obratle
          {…+}{…} Kolikrát? […]
    {…} Podvrtnutí
      {…+} Jaká část páteře byla poraněna?
        {…} Krční obratle [Ano|Ne]
          {…+}{…} Kolikrát? […]
        {…} Hrudní obratle [Ano|Ne]
          {…+}{…} Kolikrát? […]
        {…} Bederní a/nebo křížové obratle
          {…+}{…} Kolikrát? […]
    {…} Vykloubení, vymknutí (luxace), natržení nebo přetržení vazů a šlach [Ano|Ne]
      {…+} Jaká část páteře byla poraněna?
        {…} Krční obratle [Ano|Ne]
          {…+}{…} Kolikrát? […]
        {…} Hrudní obratle [Ano|Ne]
          {…+}{…} Kolikrát? […]
        {…} Bederní a/nebo křížové obratle
          {…+}{…} Kolikrát? […]
    {…} Pohmoždění (kontuze) [Ano|Ne]
      {…+} Jaká část páteře byla poraněna?
        {…} Krční [Ano|Ne]
          {…+}{…} Kolikrát? […]
        {…} Hrudní [Ano|Ne]
          {…+}{…} Kolikrát? […]
        {…} Bederní a/nebo křížová [Ano|Ne]
          {…+}{…} Kolikrát? […]
    {…} Natržení, ruptura nebo zhmoždění zádového svalu [Ano|Ne]
      {…+}{…} Kolikrát? […]
    {…} Poleptání, popálení, otevřená rána na zádech [Ano|Ne]
      {…+}{…} Kolikrát? […]
    {…} Jiný úraz [Ano|Ne]
      {…} Uveď popis: […]
      {…+}{…} Kolikrát? […]

{…} Trup a orgány [Ano|Ne]
  {…+} O jaký úraz se jednalo?
    {…} Zlomenina [Ano|Ne]
      {…+} Jaká část byla poraněna?
        {…} Hrudní kost [Ano|Ne]
          {…+}{…} Kolikrát? […]
        {…} Žebra [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…ac}{…} Napravo kolikrát? […]
            {…bc}{…} Nalevo kolikrát? […]
    {…} Pohmoždění (kontuze) orgánů [Ano|Ne]
      {…+} Jaký orgán byl poraněn?
        {…} Hrdlo (hrtan, hltan, jícen, hlasivky) [Ano|Ne]
          {…+}{…} Kolikrát? […]
        {…} Plíce [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…ac}{…} Napravo kolikrát? […]
            {…bc}{…} Nalevo kolikrát? […]
        {…} Srdce [Ano|Ne]
          {…+}{…} Kolikrát? […]
        {…} Játra [Ano|Ne]
          {…+}{…} Kolikrát? […]
        {…} Slezina [Ano|Ne]
          {…+}{…} Kolikrát? […]
        {…} Slinivka (pankreas) [Ano|Ne]
          {…+}{…} Kolikrát? […]
        {…} Žaludek [Ano|Ne]
          {…+}{…} Kolikrát? […]
        {…} Tenké nebo tlusté střevo [Ano|Ne]
          {…+}{…} Kolikrát? […]
        {…} Ledviny [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…ac}{…} Napravo kolikrát? […]
            {…bc}{…} Nalevo kolikrát? […]
        {…} Močový měchýř, močová trubice, pohlavní orgány [Ano|Ne]
          {…+}{…} Kolikrát? […]
    {…} Natržení, ruptura nebo zhmoždění břišního svalu [Ano|Ne]
      {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
        {…ac}{…} Napravo kolikrát? […]
        {…bc}{…} Nalevo kolikrát? […]
    {…} Poleptání, popálení, otevřená rána [Ano|Ne] na trupu [Ano|Ne]
      {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
        {…ac}{…} Napravo kolikrát? […]
        {…bc}{…} Nalevo kolikrát? […]
    {…} Jiný úraz [Ano|Ne]
      {…} Uveď popis: […]
      {…+}{…} Kolikrát? […]

{…} Horní končetina [Ano|Ne]
  {…+} O jaký úraz se jednalo?
    {…} Zlomenina [Ano|Ne]
      {…+} Jaká část horní končetiny byla poraněna?
        {…} Lopatka [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…ac}{…} Napravo kolikrát? […]
            {…bc}{…} Nalevo kolikrát? […]
        {…} Kliční kost [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…ac}{…} Napravo kolikrát? […]
            {…bc}{…} Nalevo kolikrát? […]
        {…} Pažní kost (humerus) [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…ac}{…} Napravo kolikrát? […]
            {…bc}{…} Nalevo kolikrát? […]
        {…} Předloktí [Ano|Ne] (loketní a vřetenní kost) [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…ac}{…} Napravo kolikrát? […]
            {…bc}{…} Nalevo kolikrát? […]
        {…} Zápěstí [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…ac}{…} Napravo kolikrát? […]
            {…bc}{…} Nalevo kolikrát? […]
        {…} Záprstní kosti [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…ac}{…} Napravo kolikrát? […]
            {…bc}{…} Nalevo kolikrát? […]
        {…} Prsty [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…ac}{…} Napravo kolikrát? […]
            {…bc}{…} Nalevo kolikrát? […]
    {…} Podvrtnutí kloubu [Ano|Ne]
      {…+} Jaká část horní končetiny byla poraněna?
        {…} Rameno [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…ac}{…} Napravo kolikrát? […]
            {…bc}{…} Nalevo kolikrát? […]
        {…} Loket [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…ac}{…} Napravo kolikrát? […]
            {…bc}{…} Nalevo kolikrát? […]
        {…} Zápěstí [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…ac}{…} Napravo kolikrát? […]
            {…bc}{…} Nalevo kolikrát? […]
        {…} Prsty [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…ac}{…} Napravo kolikrát? […]
            {…bc}{…} Nalevo kolikrát? […]
    {…} Vykloubení, vymknutí (luxace), natržení nebo přetržení vazů a šlach [Ano|Ne]
      {…+} Jaká část horní končetiny byla poraněna?
        {…} Rameno [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…ac}{…} Napravo kolikrát? […]
            {…bc}{…} Nalevo kolikrát? […]
        {…} Loket [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…ac}{…} Napravo kolikrát? […]
            {…bc}{…} Nalevo kolikrát? […]
        {…} Zápěstí [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…ac}{…} Napravo kolikrát? […]
            {…bc}{…} Nalevo kolikrát? […]
        {…} Prsty [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…ac}{…} Napravo kolikrát? […]
            {…bc}{…} Nalevo kolikrát? […]
    {…} Pohmoždění (kontuze) [Ano|Ne]
      {…+} Jaká část horní končetiny byla poraněna?
        {…} Rameno [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…ac}{…} Napravo kolikrát? […]
            {…bc}{…} Nalevo kolikrát? […]
        {…} Loket [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…ac}{…} Napravo kolikrát? […]
            {…bc}{…} Nalevo kolikrát? […]
        {…} Zápěstí [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…ac}{…} Napravo kolikrát? […]
            {…bc}{…} Nalevo kolikrát? […]
        {…} Prsty [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…ac}{…} Napravo kolikrát? […]
            {…bc}{…} Nalevo kolikrát? […]
        {…} Předloktí [Ano|Ne] (loketní a vřetenní kost) [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…ac}{…} Napravo kolikrát? […]
            {…bc}{…} Nalevo kolikrát? […]
        {…} Svaly paže (nadloktí) [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…ac}{…} Napravo kolikrát? […]
            {…bc}{…} Nalevo kolikrát? […]
    {…} Natržení nebo přetržení (ruptura) svalu [Ano|Ne]
      {…+} Jaká část horní končetiny byla poraněna?
        {…} Svaly ramenní a lopatkové [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…ac}{…} Napravo kolikrát? […]
            {…bc}{…} Nalevo kolikrát? […]
        {…} Svaly předloktí [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…ac}{…} Napravo kolikrát? […]
            {…bc}{…} Nalevo kolikrát? […]
        {…} Svaly paže (nadloktí) [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…ac}{…} Napravo kolikrát? […]
            {…bc}{…} Nalevo kolikrát? […]
    {…} Poleptání, popálení, otevřená rána [Ano|Ne]
      {…+} Jaká část horní končetiny byla poraněna?
        {…} Rameno [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…ac}{…} Napravo kolikrát? […]
            {…bc}{…} Nalevo kolikrát? […]
        {…} Loket [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…ac}{…} Napravo kolikrát? […]
            {…bc}{…} Nalevo kolikrát? […]
        {…} Zápěstí [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…ac}{…} Napravo kolikrát? […]
            {…bc}{…} Nalevo kolikrát? […]
        {…} Prsty [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…ac}{…} Napravo kolikrát? […]
            {…bc}{…} Nalevo kolikrát? […]
        {…} Předloktí [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…ac}{…} Napravo kolikrát? […]
            {…bc}{…} Nalevo kolikrát? […]
        {…} Paže (nadloktí) [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…ac}{…} Napravo kolikrát? […]
            {…bc}{…} Nalevo kolikrát? […]
    {…} Jiný úraz [Ano|Ne]
      {…} Uveď popis: […]
      {…+}{…} Kolikrát? […]

{…} Dolní končetina [Ano|Ne]
  {…+} O jaký úraz se jednalo?
    {…} Zlomenina [Ano|Ne]
      {…+} Jaká část dolní končetiny byla poraněna?
        {…} Pánev [Ano|Ne]
          {…+}{…} Kolikrát? […]
        {…} Kyčel [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…ac}{…} Napravo kolikrát? […]
            {…bc}{…} Nalevo kolikrát? […]
        {…} Stehenní kost [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…ac}{…} Napravo kolikrát? […]
            {…bc}{…} Nalevo kolikrát? […]
        {…} Čéška [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…ac}{…} Napravo kolikrát? […]
            {…bc}{…} Nalevo kolikrát? […]
        {…} Holenní a lýtková kost [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…ac}{…} Napravo kolikrát? […]
            {…bc}{…} Nalevo kolikrát? […]
        {…} Kotník (hlezno) [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…ac}{…} Napravo kolikrát? […]
            {…bc}{…} Nalevo kolikrát? […]
        {…} Pata [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…ac}{…} Napravo kolikrát? […]
            {…bc}{…} Nalevo kolikrát? […]
        {…} Nártní (metatarzální) kosti [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…ac}{…} Napravo kolikrát? […]
            {…bc}{…} Nalevo kolikrát? […]
        {…} Prsty [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…ac}{…} Napravo kolikrát? […]
            {…bc}{…} Nalevo kolikrát? […]
    {…} Podvrtnutí kloubu [Ano|Ne]
      {…+} Jaká část dolní končetiny byla poraněna?
        {…} Kyčel [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…ac}{…} Napravo kolikrát? […]
            {…bc}{…} Nalevo kolikrát? […]
        {…} Koleno [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…ac}{…} Napravo kolikrát? […]
            {…bc}{…} Nalevo kolikrát? […]
        {…} Kotník (hlezno) [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…ac}{…} Napravo kolikrát? […]
            {…bc}{…} Nalevo kolikrát? […]
        {…} Prsty [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…ac}{…} Napravo kolikrát? […]
            {…bc}{…} Nalevo kolikrát? […]
    {…} Vykloubení, vymknutí (luxace), natržení nebo přetržení vazů a šlach [Ano|Ne]
      {…+} Jaká část dolní končetiny byla poraněna?
        {…} Kyčel [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…ac}{…} Napravo kolikrát? […]
            {…bc}{…} Nalevo kolikrát? […]
        {…} Koleno [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…ac}{…} Napravo kolikrát? […]
            {…bc}{…} Nalevo kolikrát? […]
        {…} Kotník (hlezno) [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…ac}{…} Napravo kolikrát? […]
            {…bc}{…} Nalevo kolikrát? […]
        {…} Prsty [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…ac}{…} Napravo kolikrát? […]
            {…bc}{…} Nalevo kolikrát? […]
    {…} Pohmoždění (kontuze) [Ano|Ne]
      {…+} Jaká část dolní končetiny byla poraněna?
        {…} Kyčel [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…ac}{…} Napravo kolikrát? […]
            {…bc}{…} Nalevo kolikrát? […]
        {…} Koleno [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…ac}{…} Napravo kolikrát? […]
            {…bc}{…} Nalevo kolikrát? […]
        {…} Kotník (hlezno) [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…ac}{…} Napravo kolikrát? […]
            {…bc}{…} Nalevo kolikrát? […]
        {…} Prsty [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…ac}{…} Napravo kolikrát? […]
            {…bc}{…} Nalevo kolikrát? […]
        {…} Stehno [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…ac}{…} Napravo kolikrát? […]
            {…bc}{…} Nalevo kolikrát? […]
        {…} Bérec (holeň nebo lýtko) [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…ac}{…} Napravo kolikrát? […]
            {…bc}{…} Nalevo kolikrát? […]
    {…} Natržení nebo přetržení (ruptura) svalu [Ano|Ne]
      {…+} Jaká část dolní končetiny byla poraněna?
        {…} Svaly kyčelního kloubu (vč. hýžďového) [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…ac}{…} Napravo kolikrát? […]
            {…bc}{…} Nalevo kolikrát? […]
        {…} Svaly stehna [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…ac}{…} Napravo kolikrát? […]
            {…bc}{…} Nalevo kolikrát? […]
        {…} Svaly bérce (holeň nebo lýtko) [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…ac}{…} Napravo kolikrát? […]
            {…bc}{…} Nalevo kolikrát? […]
    {…} Poleptání, popálení, otevřená rána [Ano|Ne]
      {…+} Jaká část dolní končetiny byla poraněna?
        {…} Kyčle (vč. hýžďového svalu) [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…ac}{…} Napravo kolikrát? […]
            {…bc}{…} Nalevo kolikrát? […]
        {…} Koleno [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…ac}{…} Napravo kolikrát? […]
            {…bc}{…} Nalevo kolikrát? […]
        {…} Kotník (hlezno) [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…ac}{…} Napravo kolikrát? […]
            {…bc}{…} Nalevo kolikrát? […]
        {…} Prsty [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…ac}{…} Napravo kolikrát? […]
            {…bc}{…} Nalevo kolikrát? […]
        {…} Stehno [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…ac}{…} Napravo kolikrát? […]
            {…bc}{…} Nalevo kolikrát? […]
        {…} Bérec (holeň nebo lýtko) [Ano|Ne]
          {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…ac}{…} Napravo kolikrát? […]
            {…bc}{…} Nalevo kolikrát? […]
    {…} Jiný úraz [Ano|Ne]
      {…} Uveď popis: […]
      {…+}{…} Kolikrát? […]

{…} Nic z výše uvedeného [Ano|Ne]
