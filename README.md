# 📚 Binfind

BinFind is an innovative app that helps you locate the nearest trash bins in Tokyo. With just a few clicks, you can find the nearest bin to dispose of your waste and keep the city clean.


_DROP SCREENSHOT HERE_
![IMG_6250](https://user-images.githubusercontent.com/51001611/224601263-21b0137e-abb9-4650-a04e-560bb3a5f159.png)

<br>
App home: https://www.binfind.online/
   

## Getting Started
### Setup

Install gems
```
bundle install
```
Install JS packages
```
yarn install
```
### ENV Variables
Create `.env` file
```
touch .env
```
Inside `.env`, set these variables. For any APIs, see group Slack channel.
```
MAPBOX_API_KEY=your_own_mapbox_api_key
```
CLOUDINARY_URL=your_own_cloudinary_url_key
```

### DB Setup
```
rails db:create
rails db:migrate
rails db:seed
rails bin:attach_photos
```

### Run a server
```
rails s
```

## Built With
- [Rails 7](https://guides.rubyonrails.org/) - Backend / Front-end
- [Stimulus JS](https://stimulus.hotwired.dev/) - Front-end JS
- [Heroku](https://heroku.com/) - Deployment
- [PostgreSQL](https://www.postgresql.org/) - Database
- [Bootstrap](https://getbootstrap.com/) — Styling
- [Figma](https://www.figma.com) — Prototyping

## Team Members
- [Julien Afonso](https://www.linkedin.com/in/julien-afonso-59568124b/)
- [Ruka Okuyama](https://www.linkedin.com/in/luka-okuyama-14b87213a/)
- [Wanyu Jiang](https://www.linkedin.com/in/wanyu-jiang-144195248/)
- [Kevin Tsai] (https://www.linkedin.com/in/kevin-s-tsai/)
