Mug instance homeMade
this.volumeInCups = 1.5;
this.hasThumbHole = true;
this.maker = 'me';
this.color = 'blue';
this.availableVolume = {
  constructor(amtDrank)
  this.availableVolume = volumeInCups - amtDrank;
}
Methods
homeMade.canPaint('teal') = would reassign colors value to teal
homeMade.canBreak() = would reassign hasThumbHole to false
homeMade.canDrink(.5) = would reassign availableVolume to 1
homeMade.canAddThumbhole() = would reassign hasThumbHole back to true
