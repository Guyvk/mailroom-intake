# mailroom-intake

A one-page form for leaving your contact details with Guy van Koolwijk.
Published at https://guyvk.github.io/mailroom-intake/.

The key in `index.html` is a Supabase *publishable* key, public by design:
the table it reaches accepts one new row and nothing else — it cannot read,
change or delete anything. The source of this page lives in a private repo;
this one only publishes it.
