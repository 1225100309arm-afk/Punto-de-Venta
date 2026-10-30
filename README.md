# Punto de Venta Dolores

Flutter + SQLite local · TDD · Arquitectura en 3 capas.

```
lib/
  dominio/        reglas del negocio (Dart puro)
  datos/          SQLite y repositorios
  presentacion/   ViewModel y pantalla
  main.dart       composition root
test/             dominio_test.dart, datos_test.dart
docs/             manual original
```

## Uso
```
flutter create .     # genera android/ios (solo la primera vez)
flutter pub get
flutter test
flutter run
```
