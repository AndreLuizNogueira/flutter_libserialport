# Alterações

## 0.5.5

* Atualizado para Flutter 3.47.4 (Dart 3.13.3), fixado via FVM (.fvmrc);
* Android: Gradle 8.11.1 -> 9.3.1, AGP 8.2.2/8.7.3 -> 9.1.0, Kotlin 1.9.20 -> 2.4.0;
* Android: compileSdk/targetSdk 35 -> 36, minSdk 23 -> 24;
* Android: migrado 'rootProject.buildDir' para 'layout.buildDirectory' (removido no Gradle 9);
* Android: 'lintOptions' -> 'lint', 'compileSdkVersion' -> 'compileSdk', 'kotlinOptions' -> 'kotlin { compilerOptions }';
* Android: removido 'android.enableJetifier' (obsoleto) e ajustado org.gradle.jvmargs;

## 0.5.4

* Migração para Built-in Kotlin (Flutter 3.44.0+);
* Removidas dependências manuais do Kotlin Gradle Plugin e aplicação manual de 'kotlin-android';

## 0.5.3

Atualizado libserialport para Suportar Melhor o Android;

## 0.5.2

Removido import io.flutter.plugin.common.PluginRegistry.Registrar para Corrigir Erro De Build;

## 0.5.1

Atualizado Pacotes;
Atualizado MinSdk de 16 para 23 e Target de 34 para 35;
Atualizado Flutter para 3.27;
Corrigido App Exemplo e Atualizado Jdk, Kotlin e Gradle;

## 0.5.0

* Add namespace for Android
* Update Kotlin to 2.0.0

## 0.4.0

* Upgrade libserialport sources to 0.1.1
* Fix TERMIOX definition

## 0.3.0

* Upgrade to Dart 2.17, Flutter 3.0, libserialport 0.3

## 0.2.3

* Fix linux builds for newer kernels (thanks @sitic)

## 0.2.2

* Example: add serial device entitlement for macOS.

## 0.2.1

* Fix build error on Ubuntu 16.04.

## 0.2.0

* Rename from flutter_serial_port to flutter_libserialport
  <https://github.com/jpnurmi/flutter_libserialport/issues/1>

## 0.1.1

* Switch from dart_serial_port to libserialport.

## 0.1.0

* Upgraded SDK constraint & dart_serial_port dependency.

## 0.0.1

* Initial release.
