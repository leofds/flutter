# Como fazer

## Atualizar um Widget stateFul

```dart
setState((){ 
  
});
```

## TextField bordas arredondadas

```dart
TextField(
  decoration: InputDecoration(
    border: OutlineInputBorder(
        borderRadius: BorderRadius.circular(100.0)),
  ),
),
```

## ElevatedButton bordas arredondadas

```dart
ElevatedButton(
  onPressed: (){},
  child: Text('Press'),
  style: ElevatedButton.styleFrom(
      shape: StadiumBorder(), primary: Colors.orange),
),
```

## Esconder o teclado

```dart
FocusScope.of(context).requestFocus(FocusNode());
```
