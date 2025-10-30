# Kooperativa - zdravotní zkoumání
https://knz.koop.cz/KoopLifeWeb/faces/p1FN/tab_main.xhtml#

## Legenda
{A}, {B}, → {Z}: označení kapitoly
  <male|female>: celá vnořená sekce platí pouze pro uvedené pohlaví
  {1}, {2}, → {x}: číslo odpovědi pro otázku v dané v sekci (kontext/začátek otázky může být i na předcházejících vyšších úrovních)
    […]: pole na vyplnění odpovědi textem
    [a|b|→|z]: volba z možných odpovědí
  {1+}, {1-}, {1?}: číslo otázky a zástupné symboly odpovědí: [Ano|Ne|Nevím]
  {1a}, {1c}, → {1z}: číslo otázky a pořadí odpovědi při volbě ze seznamu [a|b|→|z] pro stromové pokračování

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
        {…} Ledviny / ledvin [Ano|Ne]
          {…+}{…} Prodělala jste toto onemocnění **v posledních 10 letech**? [Ano|Ne]
            {…+}{…} Máte v současné době toto onemocnění? [Ano|Ne]
        {…} Močového měchýře [Ano|Ne]
          {…+}{…} Prodělala jste toto onemocnění **v posledních 10 letech**? [Ano|Ne]
            {…+}{…} Máte v současné době toto onemocnění? [Ano|Ne]
        {…} Tlustého střeva nebo konečníku (rekta) [Ano|Ne]
          {…+}{…} Prodělala jste toto onemocnění **v posledních 10 letech**? [Ano|Ne]
            {…+}{…} Máte v současné době toto onemocnění? [Ano|Ne]
        {…} Plíce / plic [Ano|Ne]
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
            {…} Rameno [Ano|Ne]
              {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…} Loket [Ano|Ne]
              {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…} Zápěstí [Ano|Ne]
              {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…} Kyčel [Ano|Ne]
              {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…} Koleno [Ano|Ne]
              {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…} Kotník (hlezno) [Ano|Ne]
              {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…} Infekční nebo septická artritida [Ano|Ne]
              {…+}{…} Máte v současné době toto onemocnění? [Ano|Ne]
                {…-}{…} Zanechalo toto onemocnění deformity nebo omezení hybnosti kloubů? [Ano|Ne]
                  {…+} Na jakém kloubu?
                    {…} Rameno [Ano|Ne]
                      {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
                    {…} Loket [Ano|Ne]
                      {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
                    {…} Zápěstí [Ano|Ne]
                      {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
                    {…} Kyčel [Ano|Ne]
                      {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
                    {…} Koleno [Ano|Ne]
                      {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
                    {…} Kotník (hlezno) [Ano|Ne]
                      {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
    {…} Artróza nebo totální endoprotéza (TEP) [Ano|Ne]
      {…+}
        {…} Máte nebo jste měl/a artrózu? [Ano|Ne]
          {…+} Na jakém kloubu?
            {…} Rameno [Ano|Ne]
              {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…} Loket [Ano|Ne]
              {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…} Zápěstí [Ano|Ne]
              {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…} Kyčel [Ano|Ne]
              {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…} Koleno [Ano|Ne]
              {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…} Kotník (hlezno) [Ano|Ne]
              {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
        {…} Máte provedenou náhradu kloubu (totální endoprotéza, TEP), uvažujete o ní nebo vám byla doporučena? [Ano|Ne]
          {…+} Na jakém kloubu?
            {…} Rameno [Ano|Ne]
              {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…} Loket [Ano|Ne]
              {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…} Zápěstí [Ano|Ne]
              {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…} Kyčel [Ano|Ne]
              {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…} Koleno [Ano|Ne]
              {…+}{…} Na jaké straně? [Pravá|Levá|Pravá+Levá]
            {…} Kotník (hlezno) [Ano|Ne]
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


{…} 2.f) Onemocnění prostaty a onemocnění prsou (např. zvětšení prostaty, bulka v prsu) [Ano|Ne]
  {…+}

{…} [MUŽ] Zvětšená prostata [Ano|Ne]

{…} [ŽENA] Gynekologické obtíže [Ano|Ne]

{…} Bulka v prsu [Ano|Ne]


{…} 2.g) Infekční nemoci (např. žloutenka – hepatitida – typu A, B, C, D, E, mononukleóza, Lymeská borelióza, encefalitida, meningitida, HIV) [Ano|Ne]
  {…+}

{…} Žloutenka (hepatitida) typu A nebo E [Ano|Ne]
  {…+}{…} Máte v současné době toto onemocnění? [Ano|Ne]

{…} Žloutenka (hepatitida) typu B nebo D [Ano|Ne]

{…} Žloutenka (hepatitida) typu C [Ano|Ne]

{…} Infekční mononukleóza [Ano|Ne]

{…} Lymeská borelióza [Ano|Ne]
  {…+}{…} Máte v současné době toto onemocnění? [Ano|Ne]

{…} Encefalitida (včetně klíšťové) [Ano|Ne]
  {…+}{…} Máte v současné době toto onemocnění? [Ano|Ne]

{…} Meningitida [Ano|Ne]
  {…+}{…} Máte v současné době toto onemocnění? [Ano|Ne]

{…} HIV


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
  {…+}{…} Slepota 1 oka [Ano|Ne]
    Pravé oko [Ano|Ne]
    Levé oko [Ano|Ne]
  {…+}{…} Částečná nebo praktická slepota [Ano|Ne]
  {…+}{…} Úplná slepota [Ano|Ne]

{…} 2.k) Onemocnění sluchového ústrojí (např. pískání nebo šum v uchu – tinnitus, nedoslýchavost, hluchota) [Ano|Ne]
  {…+}

{…} Pískání nebo šum v uchu (tinnitus) [Ano|Ne]
  {…+}{…} Máte problémy nebo se léčíte v současnosti s tímto onemocněním? [Ano|Ne]

{…} Nedoslýchavost 1 ucha [Ano|Ne]

{…} Hluchota 1 ucha [Ano|Ne]

{…} Nedoslýchavost nebo částečná hluchota obou uší [Ano|Ne]

{…} Ztráta sluchu (úplná hluchota obou uší) [Ano|Ne]


{…} 2.l) Nic z výše uvedeného [Ano|Ne]
  {…+}
      {130} [ano|ne]

### {E} Onemocnění - část 3
{…} 3.a) Máte v současné době zdravotní obtíže? (nemoc, pracovní neschopnost, plánujete navštívit lékaře, probíhá u vás vyšetřování, čekáte na výsledky testů, zahájení léčby či operaci)
  {…+}
    Jsem v pracovní neschopnosti nebo nejsem schopen práce (v případě OSVČ)
      Uveďte důvod:
        {131} […]
    Mám potíže, pro které plánuji vyhledat lékaře
      Uveďte důvod:
        {132} […]
    Probíhá u mě vyšetřování, testy nebo čekám na výsledky provedených vyšetření
      Uveďte důvod:
        {133} […]
    Čekám na zahájení jakékoliv formy léčby nebo operaci
      Léčba (kromě operace)
        Uveďte důvod:
          {134} […]
      Operace
        Vyberte plánované operace
          {135} […]

{…} 3.b) Máte nebo jste měl/a přiznanou invaliditu 1., 2., 3. stupně a /nebo sníženou soběstačnost?
  {…+}
    Jste nebo jste byl/a osobou se zdravotním zněvýhodněním (např. držitel průkazu ZTP, OZZ)?
      {136} [Ano|Ne]
    Žádal/a jste o jejich přiznání?
      {137} [Ano|Ne]
    Osoba se zdravotním znevýhodněním (např. držitel průkazu ZTP nebo OZZ)
      V jaké fázi aktuálně je?
        {138} […]
      Pro jakou diagnózu, případně jaké diagnózy?
        {139} […]
    Invalidita
      V jaké fázi aktuálně je?
        {140} […]
      Pro jakou diagnózu, případně jaké diagnózy?
        {141} […]
    Snížená soběstačnost
      V jaké fázi aktuálně je?
        {142} […]
      Pro jakou diagnózu, případně jaké diagnózy?
        {143} […]

{…} 3.c) Máte nebo jste měl/a nějaké jiné onemocnění nebo potíže (mimo úrazy), které jste neuvedl v tomto dotazníku a pro které vás vyšetřoval, sledoval nebo léčil lékař?
  {…+}
    Vyberte onemocnění nebo potíže ze seznamu.
      {144} […]

### {F} Trvalé následky
{…} 4. Měl/a jste v minulosti úraz, který zanechal trvalé následky? (např. poškození kloubů, omezení hybnosti, ochrnutí, ztráta končetin nebo orgánu, pakloub, ztráta zraku nebo sluchu apod.)
  {…+}
    Na jaké části těla máte trvalý následek? Uveďte všechny trvalé následky.
      Hlava
        Na jaké části hlavy máte trvalý následek?
          Nos, ústa, krk
            Jaký máte trvalý následek?
              Ztráta nosu nebo čichu
                {145} [ano|ne]
              Ztráta jazyka
                {146} [ano|ne]
              Ztráta zubu/zubů
                {147} [ano|ne]
              Ztráta hlasu nebo poškození hlasivek
                {148} [ano|ne]
              Trvalá tracheostomie
                {149} [ano|ne]
              Jizvy (např. vzniklé poraněním nebo popálením)
                {150} [ano|ne]
              Jiný trvalý následek
                {151} […]
          Oko, ucho
            Jaký máte trvalý následek?
              Ztráta oka nebo slepota jednoho oka
                Na jaké straně?
                  {152} [Pravá|Levá]
              Ztráta zraku (úplná slepota)
                {153} [ano|ne]
              Částečná ztráta zraku (částečná slepota, praktická slepota)
                {154} [ano|ne]
              Pískání nebo šum v uchu (tinnitus)
                {155} [ano|ne]
              Ztráta ucha nebo poškození boltce
                Na jaké straně?
                  {156} [Pravá|Levá]
              Nedoslýchavost jednoho ucha
                {157} [ano|ne]
              Hluchota jednoho ucha
                {158} [ano|ne]
              Nedoslýchavost nebo částečná hluchota obou uší
                {159} [ano|ne]
              Ztráta sluchu (úplná hluchota obou uší)
                {160} [ano|ne]
              Jiný trvalý následek
                {161} […]
      Páteř
        Jaký máte trvalý následek?
          Omezení hybnosti
            {162} [ano|ne]
          Poškození páteře, míchy
            {163} [ano|ne]
      Trvalé následky trupu a orgánů
        Jaký máte trvalý následek?
          Ztráta části nebo celé plíce
            Na jaké straně?
              {164} [Pravá|Levá]
          Poškození funkce plic nebo srůsty plic
            Na jaké straně?
              {165} [Pravá|Levá]
          Ztráta prsu
            Na jaké straně?
              {166} [Pravá|Levá]
          Zúžení jícnu
            {167} [ano|ne]
          Ztráta sleziny nebo její části
            {168} [ano|ne]
          Ztráta části jater
            {169} [ano|ne]
          Ztráta jedné ledviny nebo její části
            Na jaké straně?
              {170} [Pravá|Levá]
          Ztráta obou ledvin
            {171} [ano|ne]
          Porušení funkce trávících orgánů
            {172} [ano|ne]
          Jizvy (např. vzniklé poraněním nebo popálením)
            {173} [ano|ne]
          Jiný trvalý následek
            {174} […]
      Horní končetina
        Jaký máte trvalý následek?
          Omezení hybnosti, viklavost nebo nestabilita kloubu a/nebo pakloub
            Na jakém kloubu máte trvalý následek?
              Rameno
                Na jaké straně?
                  {175} [Pravá|Levá]
              Loket
                Na jaké straně?
                  {176} [Pravá|Levá]
              Zápěstí
                Na jaké straně?
                  {177} [Pravá|Levá]
              Prsty
                Na jaké straně?
                  {178} [Pravá|Levá]
          Jiný trvalý následek
            {179} […]
          Ztráta prstu nebo horní končetiny
            Jaký máte trvalý následek?
              Ztráta prstu
                Na jaké straně?
                  {180} [Pravá|Levá]
              Ztráta horní končetiny v úrovni předloktí
                Na jaké straně?
                  {181} [Pravá|Levá]
              Ztráta horní končetiny v úrovni pažní kosti
                Na jaké straně?
                  {182} [Pravá|Levá]
              Ztráta horní končetiny v zápěstí
                Na jaké straně?
                  {183} [Pravá|Levá]
              Jiný trvalý následek
                {184} […]
          Trvalé neurologické příznaky (parestézie, brnění, ochrnutí apod.)
            {185} [ano|ne]
          Jizvy (např. vzniklé poraněním nebo popálením)
            {186} [ano|ne]
          Jiný trvalý následek
            {187} […]
      Dolní končetina
        Jaký máte trvalý následek?
          Omezení hybnosti, viklavost nebo nestabilita kloubu a/nebo pakloub
            Na jakém kloubu máte trvalý následek?
              Kyčel
                Na jaké straně?
                  {188} [Pravá|Levá]
              Koleno
                Na jaké straně?
                  {189} [Pravá|Levá]
              Kotník (hlezno)
                Na jaké straně?
                  {190} [Pravá|Levá]
          Jiný trvalý následek
            {191} […]
          Ztráta prstu nebo dolní končetiny
            Jaký máte trvalý následek?
              Ztráta prstu
                Na jaké straně?
                  {192} [Pravá|Levá]
              Ztráta v úrovni stehna
                Na jaké straně?
                  {193} [Pravá|Levá]
              Ztráta v úrovni bérce
                Na jaké straně?
                  {194} [Pravá|Levá]
              Ztráta v hlezenním kloubu (kotníku)
                Na jaké straně?
                  {195} [Pravá|Levá]
              Jiný trvalý následek
                {196} […]
          Zkrácení končetiny o 3 cm nebo více
            Pravá
              {197} […]
            Levá
              {198} […]
          Trvalé neurologické příznaky (parestézie, brnění, ochrnutí apod.)
            {199} [ano|ne]
          Jizvy (např. vzniklé poraněním nebo popálením)
            {200} [ano|ne]
          Jiný trvalý následek
            {201} […]
      Nic z výše uvedeného
        {202} [ano|ne]

### {G} Úraz
{…} 5. Měl/a jste v posledních 7 letech úraz? (např. zlomenina, podvrtnutí, vykloubení, poranění vazů a šlach, popálení, otřes mozku apod.)
  {…+}
    Jaká část těla byla poraněna? Uveďte všechna poranění.
      Hlava
        O jaký úraz se jednalo?
          Zlomenina
            Jaká část hlavy byla poraněna?
              Kosti lebky
                Kolikrát?
                  {203} […]
              Nos
                Kolikrát?
                  {204} […]
              Čelist
                Kolikrát?
                  {205} […]
          Podvrtnutí čelisti
            Kolikrát?
              {206} […]
          Vykloubení, vymknutí (luxace) čelisti
            Kolikrát?
              {207} […]
          Pohmoždění (kontuze) v oblasti hlavy
            Jaká část hlavy byla poraněna?
              Mozek
                Kolikrát?
                  {208} […]
              Oko
                Na jaké straně?
                  {209} [Pravá|Levá]
              Nos
                Kolikrát?
                  {210} […]
              Čelist
                Kolikrát?
                  {211} […]
              Jiná část hlavy
                Kolikrát?
                  {212} […]
          Poleptání, popálení, otevřená nebo tržná rána
            Kolikrát?
              {213} […]
          Otřes mozku
            Kolikrát?
              {214} […]
          Jiný úraz
            Kolikrát?
              {215} […]

      Páteř a záda
        O jaký úraz se jednalo?
          Zlomenina
            Jaká část páteře byla poraněna?
              Krční obratle
                Kolikrát?
                  {216} […]
              Hrudní obratle
                Kolikrát?
                  {217} […]
              Bederní a/nebo křížové obratle
                Kolikrát?
                  {218} […]
          Podvrtnutí
            Jaká část páteře byla poraněna?
              Krční obratle
                Kolikrát?
                  {219} […]
              Hrudní obratle
                Kolikrát?
                  {220} […]
              Bederní a/nebo křížové obratle
                Kolikrát?
                  {221} […]
          Vykloubení, vymknutí (luxace), natržení nebo přetržení vazů a šlach
            Jaká část páteře byla poraněna?
              Krční obratle
                Kolikrát?
                  {222} […]
              Hrudní obratle
                Kolikrát?
                  {223} […]
              Bederní a/nebo křížové obratle
                Kolikrát?
                  {224} […]
          Pohmoždění (kontuze)
            Jaká část páteře byla poraněna?
              Krční
                Kolikrát?
                  {225} […]
              Hrudní
                Kolikrát?
                  {226} […]
              Bederní a/nebo křížová
                Kolikrát?
                  {227} […]
          Natržení, ruptura nebo zhmoždění zádového svalu
            Kolikrát?
              {228} […]
          Poleptání, popálení, otevřená rána na zádech
            Kolikrát?
              {229} […]
          Jiný úraz
            Kolikrát?
              {230} […]

      Trup a orgány
        O jaký úraz se jednalo?
          Zlomenina
            Jaká část byla poraněna?
              Hrudní kost
                Kolikrát?
                  {231} […]
              Žebra
                Na jaké straně?
                  {232} [Pravá|Levá]
          Pohmoždění (kontuze) orgánů
            Jaký orgán byl poraněn?
              Hrdlo (hrtan, hltan, jícen, hlasivky)
                Kolikrát?
                  {233} […]
              Plíce
                Na jaké straně?
                  {234} [Pravá|Levá]
              Srdce
                Kolikrát?
                  {235} […]
              Játra
                Kolikrát?
                  {236} […]
              Slezina
                Kolikrát?
                  {237} […]
              Slinivka (pankreas)
                Kolikrát?
                  {238} […]
              Žaludek
                Kolikrát?
                  {239} […]
              Tenké nebo tlusté střevo
                Kolikrát?
                  {240} […]
              Ledviny
                Na jaké straně?
                  {241} [Pravá|Levá]
              Močový měchýř, močová trubice, pohlavní orgány
                Kolikrát?
                  {242} […]
          Natržení, ruptura nebo zhmoždění břišního svalu
            Na jaké straně?
              {243} [Pravá|Levá]
          Poleptání, popálení, otevřená rána na trupu
            Na jaké straně?
              {244} [Pravá|Levá]
          Jiný úraz
            Kolikrát?
              {245} […]

      Horní končetina
        O jaký úraz se jednalo?
          Zlomenina
            Jaká část horní končetiny byla poraněna?
              Lopatka
                Na jaké straně?
                  {246} [Pravá|Levá]
              Kliční kost
                Na jaké straně?
                  {247} [Pravá|Levá]
              Pažní kost (humerus)
                Na jaké straně?
                  {248} [Pravá|Levá]
              Předloktí (loketní a vřetenní kost)
                Na jaké straně?
                  {249} [Pravá|Levá]
              Zápěstí
                Na jaké straně?
                  {250} [Pravá|Levá]
              Záprstní kosti
                Na jaké straně?
                  {251} [Pravá|Levá]
              Prsty
                Na jaké straně?
                  {252} [Pravá|Levá]
          Podvrtnutí kloubu
            Jaká část horní končetiny byla poraněna?
              Rameno
                Na jaké straně?
                  {253} [Pravá|Levá]
              Loket
                Na jaké straně?
                  {254} [Pravá|Levá]
              Zápěstí
                Na jaké straně?
                  {255} [Pravá|Levá]
              Prsty
                Na jaké straně?
                  {256} [Pravá|Levá]
          Vykloubení, vymknutí (luxace), natržení nebo přetržení vazů a šlach
            Jaká část horní končetiny byla poraněna?
              Rameno
                Na jaké straně?
                  {257} [Pravá|Levá]
              Loket
                Na jaké straně?
                  {258} [Pravá|Levá]
              Zápěstí
                Na jaké straně?
                  {259} [Pravá|Levá]
              Prsty
                Na jaké straně?
                  {260} [Pravá|Levá]
          Pohmoždění (kontuze)
            Jaká část horní končetiny byla poraněna?
              Rameno
                Na jaké straně?
                  {261} [Pravá|Levá]
              Loket
                Na jaké straně?
                  {262} [Pravá|Levá]
              Zápěstí
                Na jaké straně?
                  {263} [Pravá|Levá]
              Prsty
                Na jaké straně?
                  {264} [Pravá|Levá]
              Předloktí (loketní a vřetenní kost)
                Na jaké straně?
                  {265} [Pravá|Levá]
              Svaly paže (nadloktí)
                Na jaké straně?
                  {266} [Pravá|Levá]
          Natržení nebo přetržení (ruptura) svalu
            Jaká část horní končetiny byla poraněna?
              Svaly ramenní a lopatkové
                Na jaké straně?
                  {267} [Pravá|Levá]
              Svaly předloktí
                Na jaké straně?
                  {268} [Pravá|Levá]
              Svaly paže (nadloktí)
                Na jaké straně?
                  {269} [Pravá|Levá]
          Poleptání, popálení, otevřená rána
            Jaká část horní končetiny byla poraněna?
              Rameno
                Na jaké straně?
                  {270} [Pravá|Levá]
              Loket
                Na jaké straně?
                  {271} [Pravá|Levá]
              Zápěstí
                Na jaké straně?
                  {272} [Pravá|Levá]
              Prsty
                Na jaké straně?
                  {273} [Pravá|Levá]
              Předloktí
                Na jaké straně?
                  {274} [Pravá|Levá]
              Paže (nadloktí)
                Na jaké straně?
                  {275} [Pravá|Levá]
          Jiný úraz
            Kolikrát?
              {276} […]

      Dolní končetina
        O jaký úraz se jednalo?
          Zlomenina
            Jaká část dolní končetiny byla poraněna?
              Pánev
                Kolikrát?
                  {277} […]
              Kyčel
                Na jaké straně?
                  {278} [Pravá|Levá]
              Stehenní kost
                Na jaké straně?
                  {279} [Pravá|Levá]
              Čéška
                Na jaké straně?
                  {280} [Pravá|Levá]
              Holenní a lýtková kost
                Na jaké straně?
                  {281} [Pravá|Levá]
              Kotník (hlezno)
                Na jaké straně?
                  {282} [Pravá|Levá]
              Pata
                Na jaké straně?
                  {283} [Pravá|Levá]
              Nártní (metatarzální) kosti
                Na jaké straně?
                  {284} [Pravá|Levá]
              Prsty
                Na jaké straně?
                  {285} [Pravá|Levá]
          Podvrtnutí kloubu
            Jaká část dolní končetiny byla poraněna?
              Kyčel
                Na jaké straně?
                  {286} [Pravá|Levá]
              Koleno
                Na jaké straně?
                  {287} [Pravá|Levá]
              Kotník (hlezno)
                Na jaké straně?
                  {288} [Pravá|Levá]
              Pata
                Na jaké straně?
                  {289} [Pravá|Levá]
              Nártní (metatarzální) kosti
                Na jaké straně?
                  {290} [Pravá|Levá]
              Prsty
                Na jaké straně?
                  {291} [Pravá|Levá]
          Vykloubení, vymknutí (luxace), natržení nebo přetržení vazů a šlach
            Jaká část dolní končetiny byla poraněna?
              Kyčel
                Na jaké straně?
                  {292} [Pravá|Levá]
              Koleno
                Na jaké straně?
                  {293} [Pravá|Levá]
              Kotník (hlezno)
                Na jaké straně?
                  {294} [Pravá|Levá]
              Prsty
                Na jaké straně?
                  {295} [Pravá|Levá]
          Pohmoždění (kontuze)
            Jaká část dolní končetiny byla poraněna?
              Kyčel
                Na jaké straně?
                  {296} [Pravá|Levá]
              Koleno
                Na jaké straně?
                  {297} [Pravá|Levá]
              Kotník (hlezno)
                Na jaké straně?
                  {298} [Pravá|Levá]
              Prsty
                Na jaké straně?
                  {299} [Pravá|Levá]
              Stehno
                Na jaké straně?
                  {300} [Pravá|Levá]
              Bérec (holeň nebo lýtko)
                Na jaké straně?
                  {301} [Pravá|Levá]
          Natržení nebo přetržení (ruptura) svalu
            Jaká část dolní končetiny byla poraněna?
              Svaly kyčelního kloubu (vč. hýžďového)
                Na jaké straně?
                  {302} [Pravá|Levá]
              Svaly stehna
                Na jaké straně?
                  {303} [Pravá|Levá]
              Svaly bérce (holeň nebo lýtko)
                Na jaké straně?
                  {304} [Pravá|Levá]
          Poleptání, popálení, otevřená rána
            Jaká část dolní končetiny byla poraněna?
              Kyčle (vč. hýžďového svalu)
                Na jaké straně?
                  {305} [Pravá|Levá]
              Koleno
                Na jaké straně?
                  {306} [Pravá|Levá]
              Kotník (hlezno)
                Na jaké straně?
                  {307} [Pravá|Levá]
              Prsty
                Na jaké straně?
                  {308} [Pravá|Levá]
              Stehno
                Na jaké straně?
                  {309} [Pravá|Levá]
              Bérec (holeň nebo lýtko)
                Na jaké straně?
                  {310} [Pravá|Levá]
          Jiný úraz
            Kolikrát?
              {311} […]

      Nic z výše uvedeného
        {312} [ano|ne]