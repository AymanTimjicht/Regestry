# Regestry

Add files via upload
In order to start this sample, please make sure that you specify the right data for establishing MySQL connection (in .env file):

DB_HOST=localhost
DB_USER=root
DB_PASS=
DB_NAME=test_nodejs_auth
Please also update google and facebook api keys, with valid ones:

FACEBOOK_APP_ID=your_fb_app_id
FACEBOOK_APP_SECRET=your_fb_app_secret

GOOGLE_CLIENT_ID=your_google_client_id
GOOGLE_CLIENT_SECRET=your_google_client_secret
After that, please execute the following commands:

npm install
npx sequelize db:migrate
nodemon App.js


Channels
https://iptv-org.github.io/api/channels.json
[
  //...
  {
    "id": "AnhuiTV.cn",
    "name": "Anhui TV",
    "alt_names": ["安徽卫视"],
    "network": "Anhui",
    "owners": ["China Central Television"],
    "country": "CN",
    "subdivision": "CN-AH",
    "city": "Hefei",
    "broadcast_area": ["s/CN-AH"],
    "languages": ["zho"],
    "categories": ["general"],
    "is_nsfw": false,
    "launched": "2016-07-28",
    "closed": "2020-05-31",
    "replaced_by": "CCTV1.cn",
    "website": "http://www.ahtv.cn/",
    "logo": "https://example.com/logo.png"
  }
  //...
]
