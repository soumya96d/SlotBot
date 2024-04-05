# Slot Bot

## Description

This Discord bot allows users to create slots for various purposes, such as selling items or offering services. It includes features like creating, renewing, holding, and unholding slots, as well as adding and removing users from slots.

## Features

- Create slots with specified durations and categories
- Renew slots with updated durations
- Hold slots temporarily
- Unhold slots when ready
- Add and remove users from slots
- Set slot rules and guidelines
- Receive notifications for slot activities

## Usage

To use the bot, follow these steps:

1. **Create a Slot:** Use the `,create` command to create a new slot. Example: `,create @user 1 d his Slot`.

2. **Add Users:** Use the `,add` command to add users to a slot. Example: `,add @user`.

3. **Renew a Slot:** Use the `,renew` command to renew a slot with updated duration. Example: `,renew @user #channel 1 m/d his Slot`.

4. **Hold a Slot:** Use the `,hold` command to temporarily hold a slot.

5. **Unhold a Slot:** Use the `,unhold` command to unhold a slot.

6. **Remove Users:** Use the `,remove` command to remove users from a slot. Example: `,remove @user`.

7. **Ping Notification:** Use the `,ping` command to receive a notification in the slot channel. Example: `,ping`.

## Installation

To install the bot, follow these steps:

1. Clone the repository: `git clone https://github.com/codewithriza/SlotBot.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Set up your configuration: Create a `config.py` file with your bot token and other settings.
3. Replace token and other guild id , channel id , 2 category id in `main.py`
4. Run the bot: `python main.py`

## Contributing

Contributions are welcome! If you have any ideas or improvements, feel free to open an is sue or submit a pull request.

If you find this project useful, please consider giving it a star on GitHub! 🌟

