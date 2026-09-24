# Jupiter — офлайн-диктовка для Windows

Read in English below

**Jupiter** — локальное приложение для голосовой диктовки на Windows.

Говорите — текст появляется там, где стоит курсор: в Word, браузере, блокноте и других приложениях. Обработка речи выполняется локально на компьютере пользователя. Никакой отправки голоса на сервер.

Jupiter прошёл полный цикл разработки — от идеи и исследования технологий до рабочего Windows-релиза, установщика и системы лицензирования.

## Возможности

* голосовая диктовка в реальном времени;
* без активации кнопкой — Jupiter постоянно слушает;
* если диктовка не нужна — приложение можно поставить на паузу;
* системный трей;
* ввод текста в активное Windows-приложение;
* локальная обработка речи;
* система лицензирования;
* готовый Windows-установщик.

## Технологии

* Python
* ONNX Runtime
* Sherpa-ONNX
* Windows API
* Nuitka
* Inno Setup

## О проекте

Jupiter — это три слова:

**Локально. Быстро. Просто.**

Это не универсальный AI-ассистент с десятками функций. Jupiter делает одну вещь — превращает речь в текст непосредственно в активном приложении.

Приложение работает в фоне и находится в системном трее. Не нужно открывать большое окно или постоянно нажимать кнопку: говорите — текст появляется на экране, поставили на паузу — Jupiter перестал слушать.

При разработке отдельно тестировали разные технологии распознавания речи и варианты локальной обработки. В результате получился самостоятельный Windows-продукт с нативным вводом текста, фоновой работой, упаковкой в установщик и лицензированием.

## Кому подойдёт

Врачам, юристам, писателям, тем, кто много общается с нейросетями, журналистам.... - в общем всем тем кто много работает с текстом.

## Скачать

Ссылка на актуальный Windows-релиз будет добавлена здесь.

## Скриншоты и демонстрация

Будут добавлены в следующих версиях README.

## Исходный код

Исходный код Jupiter не публикуется.

Этот репозиторий предназначен для демонстрации проекта, его возможностей и готового продукта.

---

# Jupiter — Offline Windows Voice Dictation

**Jupiter** is a local voice dictation application for Windows.

Speak naturally and the recognized text is entered directly into the active Windows application. Speech processing runs locally on the user's computer, without sending voice data to a remote server.

Jupiter was developed as a complete software product — from the initial idea and technology research to a working Windows release, installer, and licensing system.

## Features

* real-time voice dictation;
* automatic speech recognition without pressing a button;
* pause mode;
* direct text input into Windows applications;
* system tray integration;
* local speech processing;
* license and trial system;
* ready-to-use Windows installer.

## Technology

* Python
* ONNX Runtime
* Sherpa-ONNX
* Windows API
* Nuitka
* Inno Setup

## About the Project

Jupiter is a focused dictation tool built around a simple idea:

**Local. Fast. Simple.**

Instead of trying to be a universal AI assistant, Jupiter focuses on one task — converting speech into text directly inside the application the user is working with.

The application runs in the background and is controlled through the system tray. It does not require a large interface or constant button presses.

During development, different speech recognition technologies and local processing approaches were researched and tested. The final product combines speech recognition, Windows integration, background operation, application packaging, and licensing into a standalone Windows application.

## Privacy

Jupiter is designed around local speech processing.

The core dictation function does not require the user's voice to be sent to a remote server.

## Download

A link to the latest Windows release will be added here.

## Screenshots & Demo

Screenshots and a demonstration video will be added in future updates.

## Source Code

The Jupiter source code is not publicly available.

This repository is intended to showcase the project, its capabilities, and the finished product.
