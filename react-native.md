# React-Native
### Resumen
Framework creado en javascript que tiene como objeto poder crear aplicaciones móviles nativas tanto para iOs como Andriod.
### Navegar entre pantallas
Se debe instalar en la carpeta raíz del proyecto:

`npm install --save react-navigation`

`yarn add react-native-gesture-handler`

Posteriormente la app raíz debe contener:

``` 
import {createStackNavigator, createAppContainer} from 'react-navigation';
import HomeScreen from './src/Components/HomeScreen';
import ProfileScreen from './src/Components/ProfileScreen';
const MainNavigator = createStackNavigator({
  Home: {screen: HomeScreen},
  Profile: {screen: ProfileScreen},
});

const App = createAppContainer(MainNavigator);

export default App;
```  

Donde Home y Profile son componentes que se encuentran en los directorios mencionados en los import.

Cada componente debe contener dentro del bloque `render()` lo siguiente:

`const {navigate} = this.props.navigation;`

Ejemplo de Profile con texto sencillo:

```
export class Profile extends React.Component {
    static navigationOptions = {
        title: 'Profile Title',
    };
    render(){
        const {navigate} = this.props.navigation;
        return (
            <View style={styles.container}>
                <Text> This is a profile.</Text>
            </View>
        );
}}
const styles = StyleSheet.create({
    container: {
        flex: 1,
        flexDirection: 'column',
        backgroundColor: 'powderblue',
        alignItems: 'center',
        justifyContent: 'center',
    },
});

export default Profile;
``` 
