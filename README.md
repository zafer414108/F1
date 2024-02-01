# F1 

This code is a React Native app that displays a list of race items. Here's how it works:

It imports the necessary components and libraries, including StatusBar , StyleSheet , FlatList , SafeAreaView , ActivityIndicator , useFonts , and dayjs .

It imports a JSON file containing the race data and assigns it to the races variable.

The App function is exported as the default component.

Inside the App function, the useFonts hook is used to load custom fonts.

If the fonts are not yet loaded, an ActivityIndicator is displayed.

The races array is sorted based on the race dates using the sort method and the dayjs library.

The sorted races array is passed as the data prop to the FlatList component.

The renderItem prop of the FlatList specifies a callback function that renders each race item using the RaceListItem component.

The RaceListItem component is imported from the specified file and receives the item and round props.

Finally, the app returns a SafeAreaView with the styles.container style, containing the FlatList , StatusBar , and other necessary components.

The styles object defines the container style, which sets flex to 1 and backgroundColor to 'whitesmoke'.


Let me know if you need any further assistance!
Screen Gif 


https://github.com/zafer414108/F1/assets/147662873/d86fca99-c2ed-47e9-bc94-6b7d9504626a

