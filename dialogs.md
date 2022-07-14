# Dialogs

## SnackBar

```dart
ScaffoldMessenger.of(context).showSnackBar(
  SnackBar(
    content: Text('Sucesso'),
    backgroundColor: Colors.grey,
    action: SnackBarAction(
      label: 'Desfazer',
      textColor: const Color(0xff00d7f3),
      onPressed: (){
        setState(() {});
      },
    ),
    duration: const Duration(seconds: 5),
  )
);
```

Remove a snack anterior

```dart
ScaffoldMessenger.of(context).clearSnackBars();
```

## Alert

```dart
showDialog(
  context: context,
  builder: (context) => AlertDialog(
    title: Text('Mensagem?'),
    content: Text('Sucesso'),
    actions: [
      TextButton(
        onPressed: () {
          Navigator.of(context).pop();
        },
        style: TextButton.styleFrom(primary: Color(0xff00d7f3)),
        child: Text('OK')
      ),
    ],
  )
);
```
