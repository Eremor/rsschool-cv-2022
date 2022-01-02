# Artem Smirnov

## Junior Frontend Developer

## Contact information:
* __City:__ Kazan
* __Email:__ [eremidz@yahoo.com](eremidz@yahoo.com)
* __Skype:__ set..13
* __Discord:__ ArtemS#5304
* __Github:__ [Eremor](https://github.com/Eremor)

## Summary

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