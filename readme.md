# Launcher Password: tori5566

Make sure to leave a star if this repository helped you!

## Website

Warzone's website is built with React. This ties in with Warzone's [TGM](https://github.com/Warzone/TGM) project to display information like player leaderboards, individual player stats, as well as detailed match info.

## Contributing

### Setup

1. Setup the [API](https://github.com/Warzone/api) and a Spigot server connected to the API running the [TGM](https://github.com/Warzone/TGM) plugin configured and running correctly. The API is what the website relies on to get info like player stats and match info.

2. Make sure you have Node.js installed on the server. Run `yarn` (or `npm install`) to install all of the dependencies.

3. Create a `config.json` file **in the src/ directory** that looks like this:

```json
{
	"API_BASE": "YOUR_API_URL"
}
```

4. Start the development server with `yarn start` (or `npm run start`). You can also build the project with `yarn build` (or `npm run build`).

### Developer Notes

- We use [Prettier](https://prettier.io/). If you want to setup Prettier locally make sure to use our `.prettierrc`. This is optional as we have a GitHub bot that formats files if they're not already formatted correctly.
- The site was not built with self-hosting in mind. This means important links like the Discord server and store are hardcoded at the moment.