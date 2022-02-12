# React Native Scrollable Tab View Loopable

### inspired by react-native-loop-scrollable-tab-view

forked from bitQ2019/react-native-loop-scrollable-tab-view

# start 

```bash
  npm install react-native-loop-scrollable-tab-view
```


```js
import LoopScrollTabView from 'react-native-loop-scrollable-tab-view'

<LoopScrollTabView
    renderTabBar={() => <TabBar />}
    >
    {data.map((item, index) => (
        <CategoryView
        key={item.id}
        actions={actions}
        index={index}
        navigation={navigation}
        selectedId={selectedId}
        subCategories={item.sub_category}
        tabLabel={item.name}
        />
    ))}
</LoopScrollTabView>
```
