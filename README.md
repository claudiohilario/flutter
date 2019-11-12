# Testes com flutter
## Instalação
https://flutter.dev/docs/get-started/install/macos
Download - https://storage.googleapis.com/flutter_infra/releases/stable/macos/flutter_macos_v1.9.1+hotfix.6-stable.zip

```
cd ~/
mkdir development
unzip ~/Downloads/flutter_macos_v1.9.1+hotfix.6-stable.zip
```

### Configuração PATH

```
vim ~/.zshrc
```
Adicionar:
```
#Flutter
export PATH="$PATH:$HOME/development/flutter/bin"
```

### Todas as plataformas

```
flutter precache --all-platforms
```

### Create App
```
flutter create my_app_name
```
