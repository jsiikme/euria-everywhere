# Privacy Policy — Sovereign AI Panel

_Last updated: 2026-07-14 · Unofficial project, not affiliated with Infomaniak._

**English below · [Version française plus bas](#politique-de-confidentialité--français)**

## English

Sovereign AI Panel is a browser extension that lets you summarize, extract key
points, look up a term and translate web pages using **your own** Infomaniak AI
Services account.

### What the extension does with your data

- **Page content and your questions** are sent **only** when you explicitly
  trigger an action (button, context menu, keyboard shortcut, or a typed
  question). When you do, the extension sends the visible text of the current
  page, its title and URL, and your prompt to the Infomaniak AI Services API.
- Requests go **directly from your browser to `https://api.infomaniak.com`**,
  authenticated with **your own API token**. The API URL is built in code from a
  fixed template (that domain only), so the request cannot be sent anywhere else.
- Processing happens on **Infomaniak's infrastructure in Europe (Switzerland)**,
  under [Infomaniak's own terms and privacy policy](https://www.infomaniak.com/en/legal).

### What the developer receives

- **Nothing.** The developer of this extension does not collect, receive, store,
  or have access to any of your data. There is **no analytics, no telemetry, no
  tracking, and no third-party server** operated by this project.

### Data stored locally on your device

- **Settings** (your API token, AI Services product ID, model, page-size limit) are stored in
  the browser's local extension storage (`storage.local`), on your device only,
  and are never transmitted anywhere except in the `Authorization` header of the
  requests you make to Infomaniak.
- **Per-page conversation cache**: to restore a conversation when you return to a
  page, your questions and the AI's answers are cached locally for **30 minutes**,
  for the last **16 pages**. The raw page content and the model's reasoning are
  not stored. This cache never leaves your device. Clear it with the ↺ button
  (current page) or by clearing the extension's storage.

### Your control

- Uninstalling the extension, or clearing its storage
  (`about:addons` / `brave://extensions`), removes all locally stored data.
- You can revoke or rotate your Infomaniak API token at any time in the
  Infomaniak Manager.

### Contact

Questions or issues: <https://github.com/jsiikme/sovereign-ai-panel/issues>

---

## Politique de confidentialité — Français

Sovereign AI Panel est une extension de navigateur qui permet de résumer,
extraire les points clés, rechercher un terme et traduire des pages web en
utilisant **votre propre** compte Infomaniak AI Services.

### Ce que l'extension fait de vos données

- **Le contenu de la page et vos questions** ne sont envoyés **que** lorsque vous
  déclenchez explicitement une action (bouton, menu contextuel, raccourci
  clavier, ou une question saisie). L'extension transmet alors le texte visible
  de la page courante, son titre et son URL, ainsi que votre requête à l'API
  Infomaniak AI Services.
- Les requêtes partent **directement de votre navigateur vers
  `https://api.infomaniak.com`**, authentifiées avec **votre propre jeton API**.
  L'URL de l'API est construite par le code à partir d'un gabarit figé (ce
  domaine uniquement) : la requête ne peut pas être envoyée ailleurs.
- Le traitement a lieu sur **l'infrastructure d'Infomaniak, en Europe (Suisse)**,
  selon les [conditions et la politique de confidentialité d'Infomaniak](https://www.infomaniak.com/fr/legal).

### Ce que le développeur reçoit

- **Rien.** Le développeur de cette extension ne collecte, ne reçoit, ne stocke
  et n'a accès à aucune de vos données. Il n'y a **aucun analytics, aucune
  télémétrie, aucun suivi, ni aucun serveur tiers** exploité par ce projet.

### Données stockées localement sur votre appareil

- **Les réglages** (jeton API, identifiant de produit AI Services, modèle, taille max. de page) sont stockés
  dans le stockage local de l'extension (`storage.local`), sur votre appareil
  uniquement, et ne sont jamais transmis ailleurs que dans l'en-tête
  `Authorization` des requêtes que vous adressez à Infomaniak.
- **Cache de conversation par page** : pour restaurer une conversation quand vous
  revenez sur une page, vos questions et les réponses de l'IA sont mises en cache
  localement pendant **30 minutes**, pour les **16 dernières pages**. Le contenu
  brut de la page et le raisonnement du modèle ne sont pas stockés. Ce cache ne
  quitte jamais votre appareil. Videz-le avec le bouton ↺ (page courante) ou en
  vidant le stockage de l'extension.

### Votre contrôle

- Désinstaller l'extension, ou vider son stockage
  (`about:addons` / `brave://extensions`), supprime toutes les données locales.
- Vous pouvez révoquer ou renouveler votre jeton API Infomaniak à tout moment
  dans le Manager Infomaniak.

### Contact

Questions ou problèmes : <https://github.com/jsiikme/sovereign-ai-panel/issues>
