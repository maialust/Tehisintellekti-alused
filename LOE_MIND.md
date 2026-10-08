# Tehisintellekti alused – gümnaasiumi valikkursus (35 tundi)

Autor: Maia Lust · Tallinna Pae Gümnaasium

Selles kaustas on kursuse e-õpik LiaScripti vormingus.

## Mis kaustas on

| Fail või kaust | Mis see on |
|---|---|
| `README.md` | **Kursuse avafail LiaScriptis.** Sama sisu mis `tehisintellekti_alused.md`. LiaScript avab hoidla aadressi järgi just faili `README.md` ja võtab sellest ka kursuse kaardi pealkirja, autori ja kirjelduse. |
| `tehisintellekti_alused.md` | **Kogu õpik ühes failis**: avaleht, 7 plokki, 31 teemat ja sõnastik. Seda faili kasuta põhiõpikuna. |
| `plokid/` | Sama sisu plokkide kaupa (`plokk_1.md` … `plokk_7.md`). Iga fail on eraldi LiaScripti kursus. |
| `tunnid/` | Iga tund eraldi failina (nt `2.3_masinope.md`), lisaks iga ploki kordamine (`2_kordamine.md`) ja projektitöö juhend. Need sobivad näiteks ühe tunni jagamiseks Moodle'is või Teamsis. |
| `pildid/` | Infograafikud (SVG), kaanepildid ja kooli logo. **See kaust peab alati olema `.md` failidega samas kohas**, muidu pilte ei kuvata. |

## Iga tunni ülesehitus

Õpieesmärgid → õppetekst koos infograafikute ja värviliste kastidega → kokkuvõte ja põhimõisted → interaktiivne tööleht → enesekontroll (automaatne kontroll ja selgitused).
Iga ploki lõpus: praktilised ülesanded, arutelu, ploki enesekontrolltest (näidisvastustega).

## Kuidas õpikut avada

LiaScript loeb õpikut veebiaadressilt. Seepärast tuleb kaust esmalt veebi üles laadida. Kõige lihtsam on kasutada GitHubi:

1. Loo GitHubis uus avalik hoidla (*repository*), näiteks nimega `ti-alused`.
2. Laadi sinna **kogu selle kausta sisu**: `.md` failid ning kaustad `pildid`, `plokid` ja `tunnid`.
3. Ava GitHubis fail `tehisintellekti_alused.md` ja vajuta nuppu **Raw**. Kopeeri brauseri aadressiribalt aadress. See algab nii: `https://raw.githubusercontent.com/...`
4. Kirjuta brauserisse `https://liascript.github.io/course/?`, lisa kohe selle järele kopeeritud aadress ja vajuta Enter.

Kujundus (Pae Gümnaasiumi värvid, kastid ja tumesinised nupud) on iga faili päises. Eraldi CSS-faili ei ole vaja.

## Mida õpikus pole

Õpetaja materjalid jäid õpikust välja: tunnikavad, hindamistabelid, teoreetiline lõputest ning dokumentatsioon. Need on alles algses kaustas.
