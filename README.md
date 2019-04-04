<p align="center"><a href='https://www.omise.co'><img src='https://cdn.omise.co/assets/omise-logo-with-text.svg' height='60'></a></p>

This is a fork of the official **Omise Payment** payment extension which provides support for Omise payment gateway for store builders working with **OpenCart** version **3.x**.


**Here's the list of versions we tested on:**

- OpenCart 3.x


## Getting Started

### Installation Instructions

#### Manually

The steps below are the method to install the extension manually. This method requires the privilege to access your OpenCart file on your site.

1. Download the [Omise OpenCart latest version](https://github.com/er-manjeetsingh/omise-opencart).
2. Extract the file that you downloaded. After extracted the file, you will found a directory, **src**. Copy **all directories** that inside the directory, src, and place it into the root directory of your OpenCart site.
<p align="center"><img width="652" alt="Omise OpenCart src directory" src="https://cloud.githubusercontent.com/assets/4145121/24198843/1c14c870-0f3a-11e7-83a2-5969fe04a839.png"></p>

3. Login to your administration side. Go to **Extensions** > **Payments**.
<p align="center"><img alt="Payments menu" src="https://cloud.githubusercontent.com/assets/4145121/24200437/a4e0bdd0-0f3f-11e7-9fa5-770d082548b3.png"></p>

4. Look for **Omise Payment Gateway** and **Omise Payment Gateway - Internet Banking**, and click **green plus sign buttons** on both extensions to install them.
<p align="center"><img alt="Payments menu" src="https://cloud.githubusercontent.com/assets/245383/24449441/78133f5a-14a1-11e7-9d25-c6a92b2851d6.png"></p>

### First Time Setup

After the installation, you can configure the extension by:

1. Login to your administration side. Go to **Extensions** > **Payments**.
<p align="center"><img alt="Payments menu" src="https://cloud.githubusercontent.com/assets/4145121/24200437/a4e0bdd0-0f3f-11e7-9fa5-770d082548b3.png"></p>

2. Look for **Omise Payment Gateway** and click **blue pencil sign button** to configure the extension.
<p align="center"><img alt="Configure Omise Payment Gateway extension" src="https://cloud.githubusercontent.com/assets/4145121/24198878/3c5bb12a-0f3a-11e7-8b69-beb805fbcb7e.png"></p>

3. The system will display the Omise Payment Gateway dashboard page. Go to **Setting** page.
<p align="center"><img alt="Omise Payment Gateway dashboard page" src="https://cloud.githubusercontent.com/assets/4145121/24198879/3c5d0f02-0f3a-11e7-8c68-7a8f589103ea.png"></p>

The system will display the setting page.
<p align="center"><img alt="Omise Payment Gateway setting page" src="https://cloud.githubusercontent.com/assets/4145121/24198880/3c5d8360-0f3a-11e7-9b5b-b076504ff838.png"></p>

The table below is the settings for the extension and the description for each setting.

| Setting              | Description                                                                              |
| -------------------- | -----------------------------------------------------------------------------------------|
| Module Status        | Enables or disables the extension.                                                       |
| Payment method title | Title of Omise payment gateway shown at checkout.                                        |
| Enable test mode     | If selected, all transactions will be performed in TEST mode and TEST keys will be used. |
| Enable live mode     | If selected, all transactions will be performed in LIVE mode and LIVE keys will be used. |
| Public Key for test  | Your TEST public key can be found in your Omise dashboard.                               |
| Secret Key for test  | Your TEST secret key can be found in your Omise dashboard.                               |
| Public Key           | Your LIVE public key can be found in your Omise dashboard.                               |
| Secret Key           | Your LIVE secret key can be found in your Omise dashboard.                               |
| Enable 3D-Secure     | Enables or disables 3D-Secure payment.                                                   |
| Payment Action       | Whether or not the Omise charge to be captured after authorized.                         |

- To enable the extension, select the setting for `Module Status` to `Enabled`.

**Note:**

If the setting for `Payment Action` is set to `Auto Capture`, the Omise charge will be automatically captured after authorized. If the setting for `Payment Action` is set to `Manual Capture`, the Omise charge will be authorized only.

**Internet Banking**

4. Go to **Extensions** > **Payments**.
<p align="center"><img alt="Payments menu" src="https://cloud.githubusercontent.com/assets/4145121/24200437/a4e0bdd0-0f3f-11e7-9fa5-770d082548b3.png"></p>

5. Look for **Omise Payment Gateway - Internet Banking** and click **blue pencil sign button** to configure the extension.
<p align="center"><img alt="Configure Omise Payment Gateway - Internet Banking extension" src="https://cloud.githubusercontent.com/assets/245383/24449694/5eee4f00-14a2-11e7-9ed2-c590818f0388.png"></p>

6. The system will display the setting page.
<p align="center"><img alt="Omise Payment Gateway Internet Banking setting page" src="https://cloud.githubusercontent.com/assets/245383/24449729/7a1c0ee8-14a2-11e7-8521-b3c6416323f9.png"></p>

To enable the extension, select the setting for `Module Status` to `Enabled`.

> In order to enable **Omise Payment Gateway - Internet Banking**, **Omise Payment Gateway** must be installed and enabled.

## Contributing

Thanks for your interest in contributing to Omise OpenCart. We're looking forward to hearing your thoughts and willing to review your changes.

The following subjects are instructions for contributors who consider to submit changes and/or issues.

### Submit the changes

You're all welcome to submit a pull request. Please consider the [pull request template](https://github.com/omise/omise-opencart/blob/master/.github/PULL_REQUEST_TEMPLATE.md) and fill the form when you submit a new pull request.

Learn more about [pull request](https://help.github.com/articles/about-pull-requests).

### Submit the issue

To report problems, feel free to submit the issue through [GitHub's issue channel](https://github.com/er-manjeetsingh/omise-opencart/issues) by following the [Create an Issue Guideline](https://guides.github.com/activities/contributing-to-open-source/#contributing).

Learn more about [issue](https://guides.github.com/features/issues).

## License

This is open source software released under the [MIT License](https://github.com/omise/omise-opencart/blob/master/LICENSE).
