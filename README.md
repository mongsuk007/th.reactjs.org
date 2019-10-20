# reactjs.org

เรโป (repo) นี้ประกอบไปด้วยซอร์สโค้ด (source code) และเอกสารสำหรับ [reactjs.org](https://reactjs.org/).

## เริ่มต้นใช้งาน

### ข้อกำหนดเบื้องต้น

1. Git
1. Node: เวอร์ชั่น 8.x โดยเริ่มต้นที่ 8.4.0 หรือเวอร์ชั่นที่ใหม่กว่า
1. Yarn: ดู [เว็บไซต์ Yarn: คำแนะนำสำหรับการติดตั้ง](https://yarnpkg.com/lang/en/docs/install/)
1. A fork of the repo (for any contributions)
1. A clone of the [reactjs.org repo](https://github.com/reactjs/reactjs.org) on your local machine

### การติดตั้ง

1. `cd reactjs.org` เพื่อเข้าไปในรูทโปรเจ็กต์
1. `yarn` เพื่อติดตั้ง npm ดีเพนเดนซี (npm dependencie) ของเว็บไซต์

### ทำงานในเครื่อง

1. `yarn dev` เพื่อที่จะเริ่มต้นฮอทรีโหลดดิ้ง (hot-reloading) เซิฟเวอร์ที่กำลังพัฒนาอยู่ (สนับสนุนโดย [Gatsby](https://www.gatsbyjs.org))
1. `open http://localhost:8000` เพื่อเปิดเว็บไซต์ในบราวเซอร์ใดก็ได้ที่คุณชอบ

## การสนับสนุน

### แนวทาง

The documentation is divided into several sections with a different tone and purpose. If you plan to write more than a few sentences, you might find it helpful to get familiar with the [contributing guidelines](https://github.com/reactjs/reactjs.org/blob/master/CONTRIBUTING.md#guidelines-for-text) for the appropriate sections.

### สร้าง branch

1. `git checkout master` from any folder in your local `reactjs.org` repository
1. `git pull origin master` to ensure you have the latest main code
1. `git checkout -b the-name-of-my-branch` (replacing `the-name-of-my-branch` with a suitable name) to create a branch

### สร้างความเปลี่ยนแปลง

1. Follow the "Running locally" instructions
1. Save the files and check in the browser
  1. Changes to React components in `src` will hot-reload
  1. Changes to markdown files in `content` will hot-reload
  1. If working with plugins, you may need to remove the `.cache` directory and restart the server

### ทดสอบสิ่งที่เปลี่ยน

1. If possible, test any visual changes in all latest versions of common browsers, on both desktop and mobile.
1. Run `yarn check-all` from the project root. (This will run Prettier, ESLint, and Flow.)

### Push it

1. `git add -A && git commit -m "My message"` (replacing `My message` with a commit message, such as `Fix header logo on Android`) to stage and commit your changes
1. `git push my-fork-name the-name-of-my-branch`
1. Go to the [reactjs.org repo](https://github.com/reactjs/reactjs.org) and you should see recently pushed branches.
1. Follow GitHub's instructions.
1. If possible, include screenshots of visual changes. A Netlify build will also be automatically created once you make your PR so other people can see your change.

## การแปลภาษา

If you are interested in translating `reactjs.org`, please see the current translation efforts at [isreacttranslatedyet.com](https://www.isreacttranslatedyet.com/).


If your language does not have a translation and you would like to create one, please follow the instructions at [reactjs.org Translations](https://github.com/reactjs/reactjs.org-translation#translating-reactjsorg).

## Troubleshooting

- `yarn reset` to clear the local cache

## License
Content submitted to [reactjs.org](https://reactjs.org/) is CC-BY-4.0 licensed, as found in the [LICENSE-DOCS.md](https://github.com/open-source-explorer/reactjs.org/blob/master/LICENSE-DOCS.md) file.
