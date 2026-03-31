# Domain And Hosting Plan

## Recommended domain options

Domain нэрийг аль болох богино, санахад амар, brand-safe байлгах хэрэгтэй.

Санал болгох дараалал:

1. `brusselsmongolia.mn`
2. `brusselsbeercafe.mn`
3. `brusselsmongolia.com`
4. `brusselsbeer.mn`

## Hosting recommendation

Энэ сайт static-first бүтэцтэй тул хурд, өртөг, засвар үйлчилгээний хувьд дараах model хамгийн зөв.

### Preferred setup

- Frontend hosting: `Cloudflare Pages` эсвэл `Netlify`
- Domain DNS: `Cloudflare`
- Form handoff: `Formspree`, `Tally`, `Google Sheets`, эсвэл custom email relay
- Asset storage: built-in static hosting

### Why this setup

- Fast global CDN
- SSL certificate автоматаар
- Low maintenance
- Easy rollback
- Future expansion-д тохиромжтой

## If they want a more traditional setup

- Shared hosting боломжтой
- Гэхдээ performance, deployment workflow, future scaling нь static hosting-оос сул

## Production recommendation

Эхний launch дээр:

- Domain-ийг client эзэмшинэ
- Hosting account-ийг client нэр дээр нээнэ
- Танай баг deploy access авна

Ингэвэл ownership тодорхой, урт хугацаанд маргаан багатай.
