# Můj den

Česká offline PWA pro úkoly a každodenní péči o sebe.

## Funkce

- Jeden seznam úkolů bez kategorií, s termíny a poznámkami.
- Denní evidence vody, cvičení a bílkovin s nastavitelnými cíli.
- Historie denních výsledků a automatický přechod na nový den.
- Export a obnova JSON zálohy.
- Offline provoz přes service worker; data zůstávají v tomto zařízení.
- Zachovává kompatibilitu s localStorage klíčem `mujDenState`.

## Spuštění

Otevřete [aplikaci](https://pajutacz.github.io/muj-den/) v prohlížeči. Na Androidu ji lze přidat na plochu z nabídky prohlížeče. Po prvním načtení funguje i offline.

## Záloha

V aplikaci použijte **Záloha** pro stažení dat do souboru JSON. Při obnově vyberte dříve vytvořený soubor. Data se ukládají lokálně v prohlížeči; veřejné zveřejnění aplikace nepřenáší osobní záznamy na server.

## Nasazení

GitHub Actions workflow v `.github/workflows/deploy.yml` nasazuje statické soubory do GitHub Pages při každé změně větve `main`.
