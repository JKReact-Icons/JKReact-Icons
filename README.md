# JKReact ICONS

<p align="center">
  <img src="https://avatars.githubusercontent.com/u/168010528?s=200&v=4" /><br>
  Icons support for React
</p>

<hr>

## About JKReact-Icons :heart:

- First Icons support for React that developed in Sri Lanka
- - parallelly develop with [JKCSS](https://github.com/JKCSS-CSS-Framework) 

## Quick Start Guide :computer:

- In Your React js Project
- open Terminal and install `@jehankandy/jkreact-icons`

``` js

    npm i @jehankandy/jkreact-icons

``` 

- follow up following code

``` jsx

import React from 'react'
import {
     ZeroNumberFill,
     ZeroNumberSqureFill,
     OneNumberFill,
     OneNumberSqureFill,
     OneTwoThree,
     ZeroNumberOutLine, 
     ZeroNumberSqureOutLine,
     OneNumberOutline,
     OneNumberSqureOutLine,

     LogoAlexa,
     LogoAlipay,
     LogoAmazon,
     LogoAmd

} from 'react-icons';

const IconTest = () => {
  return (
    <div>
        <h1>IconTest</h1>

        <LogoAmd color={"red"} size={200} />


    </div>
  )
}

export default IconTest

```