# The Woodpecker Method

## 1: Hamppe – Steinitz, Vienna 1860

![](easy/001.png)

- All the black pieces are pointing towards the king: knight, bishop, rook
- Knights close to the king blocking two fleeing squares is a real threat
  - A possible problem: when knights are not guarded (protected)
- Bishop attacking another fleeing square
  - A possible problem: white knight can exchange pieces (knight takes bishop, pawn takes knight)
- Look at the king a find what are the spots missing for a mate
  - In this position, king can't go anywhere but black need a check
  - The only possible check is rook xh2 but the rook is not protected
  - King should capture rook and move to the only possible spot
  - Rook h8 check-mate

## 2: Steinitz – Wilson, London 1862

![](easy/002.png)

- Find possible ways to check the king
  - Rook f8 protected by bishop
  - d6, opening diagonal for bishop, check
- Find a way to move black bishop from d6
  - Bishop f8 is not a good move because it doesn't check, bishop can take your bishop, you open the diagonal moving the pawn, king has a new fleein square in the diagonal from your captured bishop
