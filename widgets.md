# Widgets

## MaterialApp

```dart
MaterialApp(
  home: <Widget?>,
  debugShowCheckedModeBanner: false,    // Retira a tarja de debug
  title: "Meu App",
)
```

## Text

```dart
Text(
  "Texto",
  style: TextStyle(
    fontSize: 30,
    color: Colors.white,
    fontWeight: FontWeight.w700
  )
)
```

## Container

```dart
Container(
  alignment: Alignment.center,		// Alinha o conteúdo no container
  color: ,
  child: <Widget?>,
  width: 50,
  height: 100,    // se não for definido um tamanho ele se auto ajusta ao conteúdo
  padding: ,      // espeçamento dentro do container
  margin: ,       // semelhante ao padding porém faz o afastamento fora do container
)
```
