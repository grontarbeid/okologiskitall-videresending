# økologiskitall.no → okologiskitall.no

Sender alle som går til **økologiskitall.no** (med ø) videre til
[okologiskitall.no](https://okologiskitall.no), og beholder resten av adressen
(økologiskitall.no/2032 havner på okologiskitall.no/2032).

- `index.html` og `404.html` sender videre, så alle adresser under domenet havner riktig.
- `CNAME` inneholder domenet i Punycode-form (`xn--kologiskitall-9mb.no` = økologiskitall.no),
  slik GitHub Pages krever for domener med æ, ø og å.
- Publiseres med GitHub Pages fra grenen `main`.

Selve dashbordet ligger i [grontarbeid/okologiskitall](https://github.com/grontarbeid/okologiskitall).
Ansvarlig: Grønt arbeid Nordvik, org.nr. 936 885 403.
