# Artem Smirnov

## Junior Frontend Developer

## Contact information:
* __City:__ Kazan
* __Email:__ [eremidz@yahoo.com](eremidz@yahoo.com)
* __Skype:__ set..13
* __Discord:__ ArtemS#5304
* __Github:__ [Eremor](https://github.com/Eremor)

## Summary
My main goal is to change professional activities. At the moment, I work as a systems engineer and I understand that I have come to the point where I do not have enough current work intellectually, therefore, I began to actively study programming. For these purposes, I try to allocate as much time as possible and "absorb" the information with great zeal.

## Skills
* HTML5, CCS3
* JavaScript, TypeScript
* React, Redux
* Preprocessor: SCSS
* Module bundler: Webpack
* Figma, Adobe XD

## Code examples
```JavaScript
export class GameField extends BaseComponent {
  private cards: Card[] = [];

  constructor() {
    super('div', ['game__field']);
  }

  public clear(): void {
    this.cards = [];
  }

  public addCards(cards: Card[]): void {
    this.cards = cards;
    this.cards.forEach((card): void => this.addChildren([card.node]));
    setTimeout(() => {
      this.cards.forEach((card) => card.flipToBack());
    }, SHOW_TIME * 1000);
  }
}
```

## Experience
* __Virtual piano:__ [Virtual piano demo](https://eremor.github.io/virtual-piano/), [Virtual piano code](https://github.com/Eremor/virtual-piano)
* __Photo filter:__ [Photo filter demo](https://eremor.github.io/photo-filter/), [Photo filter code](https://github.com/Eremor/photo-filter)
* __Online ZOO:__ [Online ZOO code](https://eremor.github.io/online-zoo/), [Online ZOO code](https://github.com/Eremor/online-zoo)
* __React projects:__ [React projects code](https://github.com/Eremor/react)

## Education
* __FreeCodeCamp:__ [Responsive Web Design](https://www.freecodecamp.org/certification/eremor/responsive-web-design)
* __FreeCodeCamp:__ [JavaScript Algorithms and Data Structures](https://www.freecodecamp.org/certification/eremor/javascript-algorithms-and-data-structures)
* __RSSchool:__ [React](https://app.rs.school/certificate/gg9hwt7m)

## English - A2