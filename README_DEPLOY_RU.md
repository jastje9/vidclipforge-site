# VidClipforge — готовый сайт для TikTok Developers

Пакет содержит английский сайт: `index.html`, `privacy.html`, `terms.html`, `support.html`, `styles.css`, `logo.png` (1024 × 1024), `.nojekyll`.

## Публикация на GitHub Pages

1. Создать **публичный** репозиторий `vidclipforge-site` в GitHub-аккаунте `jastje9` (если имя аккаунта другое, поменяйте ссылки ниже).
2. В репозитории нажать **Add file → Upload files**. **Распаковать ZIP и загрузить ФАЙЛЫ внутрь архива в корень репозитория**, не сам ZIP и не вложенную папку. Нажать **Commit changes**.
3. Перейти **Settings → Pages → Build and deployment → Deploy from a branch → main → /(root) → Save**.
4. Открыть сайт и убедиться, что все страницы доступны:
   - Website: `https://jastje9.github.io/vidclipforge-site/`
   - Terms: `https://jastje9.github.io/vidclipforge-site/terms.html`
   - Privacy: `https://jastje9.github.io/vidclipforge-site/privacy.html`
   - Support: `https://jastje9.github.io/vidclipforge-site/support.html`
5. В TikTok Developers → App details → Platforms → Desktop указать Website URL. Вставить URL Terms и Privacy в соответствующие поля, затем нажать Save.

## Проверка владения URL в TikTok

Текущие требования TikTok: **URL properties → Verify properties → URL prefix**. Лучше проверять URL-префикс проекта `https://jastje9.github.io/vidclipforge-site/`, а не домен `github.io`, поскольку домен github.io принадлежит GitHub, а не владельцу репозитория.

TikTok предоставит **signature file**. Скачайте именно тот файл и загрузите в репозиторий в то место, которое указано в инструкции TikTok. Убедитесь, что он доступен по публичному URL, затем нажмите Verify в TikTok. Нельзя заранее выдумать имя или содержимое файла: его выдаёт TikTok.

Если TikTok не принимает project URL-prefix / GitHub Pages, потребуется собственный домен, где можно выполнить подтверждение владения.

## Для отправки на TikTok review

Сайт НЕ гарантирует одобрение. TikTok требует рабочую API-интеграцию и видео её использования. В частности Direct Post API может ограничивать клипы приватным режимом до аудита. Согласие на использование чужих Twitch-стримов необходимо независимо от авторизации платформ.

## Контакт и юридические тексты

Политики — рабочие проекты, а не юридическая консультация. Перед публичным использованием проверьте, что утверждения о хранении токенов, обработке данных и удалении соответствуют фактической реализации VidClipforge. Контакт на странице Support сейчас ведёт на GitHub Issues будущего репозитория. Убедитесь, что Issues включены, или замените на действующий контактный адрес.

**Никогда не загружайте в репозиторий** OAuth JSON, client secret, access token, refresh token или видео с личной информацией.
