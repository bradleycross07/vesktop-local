# vesktop-local

My Vesktop build: upstream https://github.com/Vencord/Vesktop plus one change on the `local` branch.

- raise stream bitrate (for 1440p 60 fps screen sharing with Nitro)

Update: rebase `local` onto the newest upstream release, rebuild with `pnpm package:dir`,
then `git push --force-with-lease backup local`.
