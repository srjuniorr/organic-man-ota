# Organic Man Coffee — OTA

Atualizações over-the-air (OTA) do app **Organic Man Coffee**.

- **`version.json`** — última versão publicada + link do bundle.
- **Releases** — cada release carrega um `bundle.zip` (o build estático da interface do app).

## Como funciona

Ao abrir, o app lê o `version.json`, compara com a versão instalada e, se houver uma
nova, baixa o `bundle.zip` e aplica na próxima abertura (com rollback automático se falhar).
Assim dá pra atualizar a interface, o cardápio e os preços **sem reinstalar o APK**.

> Este repositório **não** contém código-fonte nem segredos — apenas o build estático
> (HTML/CSS/JS) que já vai embutido no APK. Por isso é público: o app baixa as
> atualizações sem precisar de login.
