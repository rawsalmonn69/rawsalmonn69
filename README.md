ㅤㅤㅤ
![Image](https://raw.githubusercontent.com/rawsalmonn69/rawsalmonn69/refs/heads/main/Untitled1890_20261013152656.png)
const str = '■'.repeat(48);

// Standard RGB gradient
const standardRGBGradient = gradient(['red', 'green']);

// Short HSV gradient: red -> yellow -> green
const shortHSVGradient = gradient(['red', 'green'], { interpolation: 'hsv' });

// Long HSV gradient: red -> magenta -> blue -> cyan -> green
const longHSVGradient = gradient(['red', 'green'], { interpolation: 'hsv', hsvSpin: 'long' });

console.log(standardRGBGradient(str));
console.log(shortHSVGradient(str));
console.log(longHSVGradient(str));
