# din-5008-css

Stylesheet for layouting a A4 paper according to [DIN 5008 Wikipedia](https://de.wikipedia.org/wiki/DIN_5008)  

Based on [these examples from wikimedia](https://commons.wikimedia.org/wiki/Category:DIN_5008?uselang=de)  
<table>
  <tr>
    <td align="center">
      <a href="https://raw.githubusercontent.com/grapefruit89/din-5008-css-forked-for-later/master/DIN_5008,_Form_A.svg" target="_blank">
        <img src="https://raw.githubusercontent.com/grapefruit89/din-5008-css-forked-for-later/master/DIN_5008,_Form_A.svg" width="200" alt="Form A">
      </a>
      <div><strong>Form A</strong></div>
    </td>
    <td align="center">
      <a href="https://raw.githubusercontent.com/grapefruit89/din-5008-css-forked-for-later/master/DIN_5008_Form_B.svg" target="_blank">
        <img src="https://raw.githubusercontent.com/grapefruit89/din-5008-css-forked-for-later/master/DIN_5008_Form_B.svg" width="200" alt="Form B">
      </a>
      <div><strong>Form B</strong></div>
    </td>
  </tr>
</table>


## Usage  
See [example.html](./index.html)  
[the preview on Github Pages](https://grapefruit89.github.io/din-5008-css-forked-for-later/)  









Components

- `<din-5008>`  
  Add attribute `form="B"` to use alternate format with more space in `<briefkopf>`
  Add attribute `no-markers` to hide markers
- `<briefkopf>`
- `<rucksendeangabe>`
- `<vermerkzone>`
- `<anschriftzone>`
- `<informationsblock>`
- `<textfeld>`
- `<seitenangabe>`
- `<fusszeile>`

## License

> The MIT License
>
> Copyright (C) 2022 Hannes Diercks
>
> Permission is hereby granted, free of charge, to any person obtaining a copy of
> this software and associated documentation files (the "Software"), to deal in
> the Software without restriction, including without limitation the rights to
> use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies
> of the Software, and to permit persons to whom the Software is furnished to do
> so, subject to the following conditions:
>
> The above copyright notice and this permission notice shall be included in all
> copies or substantial portions of the Software.
>
> THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
> IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
> FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
> COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
> IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
> CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
