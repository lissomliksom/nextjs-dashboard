# Todo:
---




# Notes:
---


Next/link

Routes are automatically prefetched as they become visible in the user's viewport. Prefetching happens when the page first loads or when it comes into view through scrolling.

 Any <Link /> that is in the viewport (initially or through scroll) will be preloaded. Prefetch can be disabled by passing prefetch={false}. When prefetch is set to false, prefetching will still occur on hover.

Men hva hvis jeg ikke vil prefetche i det hele tatt? 

Ansattside:
- Kontakt oss (kun adresse)
- Alle ansatte (kontaktkort med 900 personer)

Gå på Narvesen:
- Kan jeg få en kaffe, takk?
- Ja, her har du en kaffe og en pølse.
- Kan jeg få bare en kaffe, og ingenting annet?
- Ja, her har du en kaffe og en pølse.

Eller er det bare koden som prefetches, og ikke assets?

---

Postgres via Vercel:
Sjukt smart. Kan opprette og ikke minst se databasen kun via adminpanel.
Privat på Lesekloden må jeg lage en droplet hos DO, koble opp mot forge, koble opp mot git, og fortsatt må jeg bruke en lokal klient for å se databasen.

---

Hooks og props:
useSearchParams() er en client-side hook.
searchParams er en prop.
Er det slik at alle client-hooks alltid begynner med *use*?

---

Navigate to the <Pagination/> component and you'll notice that it's a Client Component. You don't want to fetch data on the client as this would expose your database secrets (remember, you're not using an API layer). Instead, you can fetch the data on the server, and pass it to the component as a prop.