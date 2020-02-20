---
title: "Getting Started"
metaTitle: "Syntax Highlighting is the meta title tag for this page"
metaDescription: "This is the meta description for this page"
---

The following is a code block with JavaScript language syntax highlighting.

## Installation

```javascript

npm install react-native-lights


```

or 


```javascript

yarn add react-native-lights

```
## Usage

```javascript

import {BottomSheet} from "react-native-lights";

const BottomSheet = () => {
     const data =
     {
       buttonText: 'card1',
       buttonStyles:{borderRadius:5,backgroundColor:"#42f5e9", buttonTextColor:"black"},
       bottomSheetStyles:{backgroundColor:"#edfcfb", textFontSize:15},
       bodyText: 'Lorem ipsum dolor sit amet et nuncat mergitur',  
     }

  return (
    <View style={{flex:1}}>
<BottomSheet data={data}/>
    </View>
  );
  
};
```
