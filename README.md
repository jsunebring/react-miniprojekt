# React-miniprojekt

Följande miniprojekt bör inte ta särskilt lång tid och används i syfte att få en känsla av er grundläggande kompetens.
I denna mapp finner ni ett helt nytt Create-React-App projekt som har skapats upp med hjälp av:

`npx create-react-app react-miniprojekt --template typescript`

## Funktionalitet

Er app ska innehålla en enkel lista och medföljande formulär för att lägga till ny lokal data.

### Lista

- Populeras med data ifrån `https://swapi.dev/api/people`. Dokumentation för API:et finner ni [här](https://swapi.dev/)
- Ni behöver enbart rendera ut **name**, **height** och **mass** för varje objekt i responsen.
- Paginering behövs inte

### Modal (formulär)

- **Ska öppnas med hjälp av knapp**
- 3 inputs (name, height och mass)
- Vid submit stängs modal och datan **adderas till den ursprungliga lista** som tidigare populerats av API-anropet.
- Validering av inputs behövs inte
- Datan som ni lägger till **ska inte vara persistent** och får försvinna vid refresh

Styling är ingen prioritet men vi ser gärna att ni stylar era komponenter på något sätt.
Fokus är på att skriva **läsbar** och **tydlig** kod med **maintainability** i fokus. Se [KISS-principen](https://en.wikipedia.org/wiki/KISS_principle)

## Kom igång

### `npm install`

### `npm start`
