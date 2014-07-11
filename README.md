# CSS MIN HEIGHT SCALE

  Mobile-first classes for css-min-height-scale.
  Set the desired css-min-height-scale on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
```
npm install --save-dev css-min-height-scale
```
or download the css on github and include in your project.

## File Size


## The Code
```
.mn-hi1   { min-height: 1rem; }
.mn-hi2   { min-height: 2rem; }
.mn-hi3   { min-height: 4rem; }
.mn-hi4   { min-height: 8rem; }
.mn-hi5   { min-height: 16rem; }
.mn-hi6   { min-height: 32rem; }
.mn-hi7   { min-height: 48rem; }
.mn-hi8   { min-height: 64rem; }
.mn-hi9   { min-height: 96rem; }
.mn-hi10  { min-height: 128rem; }

@media screen and (min-width: 48em) {
  .mn-hi1-ns   { min-height: 1rem; }
  .mn-hi2-ns   { min-height: 2rem; }
  .mn-hi3-ns   { min-height: 4rem; }
  .mn-hi4-ns   { min-height: 8rem; }
  .mn-hi5-ns   { min-height: 16rem; }
  .mn-hi6-ns   { min-height: 32rem; }
  .mn-hi7-ns   { min-height: 48rem; }
  .mn-hi8-ns   { min-height: 64rem; }
  .mn-hi9-ns   { min-height: 96rem; }
  .mn-hi10-ns  { min-height: 128rem; }
}

@media screen and (min-width: 48em) and (max-width: 64em) {
  .mn-hi1-m   { min-height: 1rem; }
  .mn-hi2-m   { min-height: 2rem; }
  .mn-hi3-m   { min-height: 4rem; }
  .mn-hi4-m   { min-height: 8rem; }
  .mn-hi5-m   { min-height: 16rem; }
  .mn-hi6-m   { min-height: 32rem; }
  .mn-hi7-m   { min-height: 48rem; }
  .mn-hi8-m   { min-height: 64rem; }
  .mn-hi9-m   { min-height: 96rem; }
  .mn-hi10-m  { min-height: 128rem; }

}

@media screen and (min-width: 64em)  {
  .mn-hi1-l   { min-height: 1rem; }
  .mn-hi2-l   { min-height: 2rem; }
  .mn-hi3-l   { min-height: 4rem; }
  .mn-hi4-l   { min-height: 8rem; }
  .mn-hi5-l   { min-height: 16rem; }
  .mn-hi6-l   { min-height: 32rem; }
  .mn-hi7-l   { min-height: 48rem; }
  .mn-hi8-l   { min-height: 64rem; }
  .mn-hi9-l   { min-height: 96rem; }
  .mn-hi10-l  { min-height: 128rem; }
}

```

## Author

[http://mrmrs.cc - Entire internet gateway to all things mrmrs](http://mrmrs.cc)
[http://mrmrs.io - Open source projects](http://mrmrs.io)

## License

The MIT License (MIT)

Copyright (c) 2014 @mrmrs

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

