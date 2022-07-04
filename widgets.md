# Widgets

Relação dos principais Widgets e suas propriedades mais comuns

## MaterialApp

```dart
MaterialApp(
  debugShowCheckedModeBanner: false,    // Retira a tarja de debug
  title: "Meu App",
  home: <Widget?>,
)
```

## Scaffold & AppBar

```dart
Scaffold(
  backgroundColor: Colors.red,
  appBar: AppBar(
    title: Text('Title'),
    centerTitle: true,
  ),
  body: <Widget?>,
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
  padding: EdgeInsets.all(10.0),      // espeçamento dentro do container
  margin: EdgeInsets.only(left: 10),       // semelhante ao padding porém faz o afastamento fora do container
)
```

## Column

```dart
Column(
  mainAxisAlignment: MainAxisAlignment.center,      // Alinha no centro da coluna
  crossAxisAlignment: CrossAxisAlignment.stretch,   // (eixo cruzado, horizontal) Tenta ocupar a máxima largura
  children: <Widget?>[]
)
```

## Row

```dart
Row(
  mainAxisAlignment: ,
  crossAxisAlignment: ,
  children: , <Widget?>[]
)
```

## Expanded

Ocupa todo o espaço disponível, como a máxima largura disponivel

```dart
Expanded(
  child: <Widget?>,
  flex:	2  // peso, agora o filho tem duas vezes o tamanho, no caso de estar em	uma row com mais um Expanded
)
```

## Padding

Adiciona espacamento em volta de um widget

```dart
Padding(
  padding: EdgeInsets.all(32),
  child: <Widget?>
)
```

## SizedBox

Cria um widget invisível, adiciona um espeçamento em uma lista, também permite aumentar a altura do botão, colocando o botão como filho e definindo o height.

```dart
SizedBox(
  width: 64,
  height: 32,
  child: <Widget?>
)
```

## Divider

Divisão entre enementos

```dart
Divider(),
```

## Center

Cntraliza o filho no espaço disponível

```dart
Center(
  child: <Widget?>
)
```

## TextButton

```dart
TextButton(
  onPressed: (){},
  style: TextButton.styleFrom(
    primary: Colors.black,              // Ao clicar o efeito do botão fica com uma cor preta
    backgroundColor: Colors.white,
    fixedSize: const Size(100, 100),    // Cuidade pois não irá redimencionar
  ),
  child: <Widget?>
)
```
