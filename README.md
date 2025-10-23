for running project open trvelmate in commandprompt:
**frontEnd:follow the commands**
1.cd sample
2.npm install
3.npm run dev
**forbackend:follow the command**
1.cd server
2.npm install
3.npx prisma generate
4.npm run dev
**for connecting your mangodb:**
in **.env** file replace existing mongodb database url with your mangodb url
and then run the following commands
-->npx prisma generate
-->npx prisma db push
-->npx prisma generate
-->npm run dev
