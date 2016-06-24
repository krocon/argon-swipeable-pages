# \<argon-swipeable-pages\>

argon-swipeable-pages is used to show one of serveral pages

![Screen](https://cloud.githubusercontent.com/assets/11378781/16348357/4ebcc948-3a52-11e6-92e7-4e5c6bf49b54.png)

## Usage

#### Example

```
    <argon-swipeable-pages items="{{elements}}" as="element" index-as="idx">
        <template>
            <div style="padding:20px;">
                <h1>[[getNumber(idx)]]) [[element]]</h1>
                <h2>Index: [[idx]]</h2>
                <h3>Element: [[element]]</h3>
            </div>
        </template>
    </argon-swipeable-pages>
```