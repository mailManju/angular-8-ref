# angular-8-ref


## source-map-explorer
###### Analyze and debug JavaScript (or Sass or LESS) code bloat through source maps.

###### The source map explorer determines which file each byte in your minified code came from. It shows you a treemap visualization to help you debug where all the code is coming from. Check out this Chrome Developer video (3:25) for a demo of the tool in action.

> [LINK : source-map-explorer](https://www.npmjs.com/package/source-map-explorer)


>  npm install -g source-map-explorer

>  ng build --prod --source-map

>  source-map-explorer bundle.min.js

>  source-map-explorer bundle.min.js bundle.min.js.map

## Application with Tree Shaking

> Disclaimer: As commenter Ben Elliot pointed out, the UglifyJs plugin used in the Webpack build is not able to remove unused Typescript classes because those, when transpiled, are implemented using IIFE. 



## Angular Element

## angular CDK

# Angular 7 release update :
[Source] (https://blog.ninja-squad.com/2018/10/18/what-is-new-angular-7/)
## 1.  Angular recently announced a new render engine called Ivy.

##### Angular view engine takes the templates and components we’ve written and translates them into regular HTML and JavaScript that the browser can read and display.
#### Ivy is the next generation of Angular Renderer. It is third in line after the original compiler (for Angular 2) and Renderer2 (for Angular 4 and above). Misko Hevery and Kara Erickson gave us the first look of Ivy in ngConf-2018.

[Source 1] (https://blog.imaginea.com/ivy-a-look-at-the-new-render-engine-for-angular/)

[Source 2] (https://herringtondarkholme.github.io/2018/02/19/angular-ivy/)

## 2.  Slots with Angular Elements

##### It is possible to use ViewEncapsulation.ShadowDom since Angular 6.1, which is great for Angular Elements (Angular components packaged as Web components that you can use alone). But there was a missing feature to be able to use <slot>, a new standard HTML element, introduced by the Web Component specification. This feature is now available, enabling components with a template like:



