# IconRender-Support
Documentation and support for IconRender

## HOW TO USE IconRender
First of all, we use [IconFont](https://www.iconfont.cn/) to manange our icons. It’s a Vector Icon Management & Communication Platform made by Alimama MUX, designers could upload vector icons here, and users could download it by several kinds of format.Also, the icons could be translated into Fonts for front-end engineers’ usage.

### 1.Download Iconfont
#### 1.1 Config Project
* Create your own IconFont Project, and open the **Project Settings**;
* Under **字体格式**, Check **TTF ✅** and Do Not Check **彩色 ❌** ;
* Click **Save** button, save those **Project Settings**.

![1 2-OpenProjectSettings](https://github.com/XSGarage/IconRender-Support/assets/12060054/d62b25ab-a394-4389-9f98-2aafa549aa66)
![1 1-ConfigProject](https://github.com/XSGarage/IconRender-Support/assets/12060054/a2ce7e68-1192-4b6d-ab18-219ff680980a)

#### 1.2 Download IconFont
![1 3-DownloadIconFont](https://github.com/XSGarage/IconRender-Support/assets/12060054/83e5e2f8-c881-401c-8a11-9a8323b7eb97)


### 2.Enable IconRender
#### 2.1 Enable IconRender plugin
* Add **Icon Render** Plugin to your project;
* Under Plugins, Search **Icon Render** plugin and enable it.

![2 1-EnablePlugin](https://github.com/XSGarage/IconRender-Support/assets/12060054/6b091486-f73e-433e-bd90-3b3ed0088c6a)


#### 2.2 Search and find IconWidget
* Under **UserWidger** panel, search and find **Icon Widget**.

![2 2-ShowIconWidget](https://github.com/XSGarage/IconRender-Support/assets/12060054/9039a56f-4582-4942-8a2f-bbc31904a0d7)


### 3.Render Icon
#### 3.1 Import Iconfont
* Import **TFF** font by **Unreal**;
* **Unreal** will generate two assets: **Font Face**, **Font**;
* **Font Face** contains your **TFF** font;
* **Font** is what we need for **Icon Widget**.

![3 1-ImportIconfont](https://github.com/XSGarage/IconRender-Support/assets/12060054/d7de5d26-f6ec-408a-8e2c-83c67f750f2c)


#### 3.2 Config IconWidget Font
* Drag and select **Icon Widget** component;
* Under tab **Detail**, find **Font** attribute under **Appearance** panel.
* Expand **Font** attribute, click **Font Family** and select **Font** asset from previose step.

![3 2-UseImportedFont](https://github.com/XSGarage/IconRender-Support/assets/12060054/73802538-34b8-4c79-bd62-f692f8c46b3b)


#### 3.3 Search Unicode and render
* Open icon detail on your project, find **Unicode** attribute and copy it;
* Open **Unreal Editor**, find the **Icon Widget** component;
* Paste to **Unicode** attribute under **Content** panel;
* Icon will render on screen;
* 🎉 Congratulation, you have learned how to use **Icon Render**;
* For Size, you can change it with **Font.Size** attribute under **Appearance** panel;
* For Color, you can change it with **Color and Opacity** attribute under **Appearance** panel;

![3 3 1-FindUnicode](https://github.com/XSGarage/IconRender-Support/assets/12060054/086b5267-64de-4610-8a83-af4a3131d07b)
![3 3 2PasteUnicode](https://github.com/XSGarage/IconRender-Support/assets/12060054/1f6fb551-dbf3-428a-977d-5b12adf8a19d)



