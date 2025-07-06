# Pokédex - Projeto Flutter/PHP

Este projeto é uma Pokédex desenvolvida com Flutter no front-end e PHP com MySQL no back-end. O objetivo é demonstrar uma integração entre um aplicativo mobile e um servidor local que fornece e recebe dados.

---

## ✅ Requisitos

- PHP 8+ instalado (nativo ou via XAMPP/WAMP)
- Flutter SDK instalado
- MySQL/MariaDB local com as tabelas esperadas
- Dispositivo Android ou emulador configurado

Os arquivos PHP devem estar configurados para responder às rotas:

- `/get_pokemon.php`
- `/sync_user.php`
- `/sync_pokemon.php`

---

## ▶️ Como rodar o servidor PHP

Abra o terminal ou Git Bash e navegue até a pasta onde estão os arquivos `.php`:

```bash
cd caminho/para/sua/api
php -S 0.0.0.0:8000
