# Safety Beacon 🚨

## The concept 💡

You've probably heard of the "angel shot", where somebody can ask at the bar for an "angel shot" if they feel unsafe on a date so the staff can (subtly) make sure they can get out/home safely.

I'm imagining a similar thing in digital form.

You sign up (requiring ID check), and then you're able to send out a "help me" notification to everyone who also has this app within a ~300m radius so they can step in to help and/or call the police.

## The plan 🥷

I'd like it to be non-for-profit and fully open source, so it's about everyone helping everyone, for the sake of keeping each other safe.

## The technology 🧑‍💻

### The Tech Stack

| Service | Technology used |
| - | - |
| [Website](https://github.com/safetybeacon/website) | [Hugo](https://gohugo.io/) |
| [Client apps (Web, iOS, Android)](https://github.com/safetybeacon/client-app) | [TypeScript](https://www.typescriptlang.org/), [React](https://react.dev/), [Chakra UI](https://chakra-ui.com/), [Zustand](https://github.com/pmndrs/zustand), [Capacitor](https://capacitorjs.com/) |
| Smart watch apps | *TBC* |
| [REST API](https://github.com/safetybeacon/beacon-api) | [Golang](https://go.dev/), [Gin](https://github.com/gin-gonic/gin), [GORM](https://gorm.io/) |
| Database | [PostgreSQL](https://www.postgresql.org/) |
| Cloud provider | [GCP](https://aws.amazon.com/) |
| Infrastructure as Code | [Terraform](https://www.terraform.io/) |

> **Note:** It's early days and the stack/architecture is subject to change.
> See current architecture plan [here](https://github.com/safetybeacon/infrastructure/blob/main/architecture_plan.md)

### Contribution guidelines

All project management is held within GitHub. Please open issues and submit pull requests!

Please include lots of comments, and use tabs to indent your code.

Your pull requests will be reviewed by the repository's code owner(s) as soon as possible.

### Software license

All code will be published under the [GNU General Public License v3.0](https://choosealicense.com/licenses/gpl-3.0/) license, allowing anyone to contribute while forbidding the distribution of closed source versions.
