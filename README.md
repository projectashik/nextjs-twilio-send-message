To use this code:

- Clone the repo

```bash
git clone https://github.com/projectashik/nextjs-twilio-send-message
```

- cd to that directory

```bash
cd nextjs-twilio-send-message
```

- run yarn or npm i

```bash
yarn # yarn users
npm i # npm users
```

- create `.env.local` file and add the following

```env
TWILIO_ACCOUNT_SID=YOUR_ACCOUNT_SID
TWILIO_AUTH_TOKEN=YOUR_AUTH_TOKEN
```

- Now, change the phone number in `pages/api/sendMessage.ts`.

```js
client.messages.create({
  body: message,
  from: 'YOUR_PHONE_NUMBER',
  to: phone,
});
```

- Run the server

```bash
yarn dev # yarn users
npm run dev # npm users
```

Read the full blog at:

Hashnode: [https://cb-ashik.hashnode.dev/heres-how-you-can-send-messages-to-your-phone-with-nextjs-and-twilio](https://cb-ashik.hashnode.dev/heres-how-you-can-send-messages-to-your-phone-with-nextjs-and-twilio)

DevDojo: [https://devdojo.com/chapagainashik/heres-how-you-can-send-messages-to-your-phone-with-nextjs-and-twilio](https://devdojo.com/chapagainashik/heres-how-you-can-send-messages-to-your-phone-with-nextjs-and-twilio)

Dev.to: [https://dev.to/chapagainashik/here-s-how-you-can-send-messages-to-your-phone-with-next-js-and-twilio-l8](https://dev.to/chapagainashik/here-s-how-you-can-send-messages-to-your-phone-with-next-js-and-twilio-l8)
