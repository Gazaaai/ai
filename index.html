import json
import requests
import os 
os.system('pip install cherrypy ')
import cherrypy
class Sin:
    @cherrypy.expose
    def index(self):
        return self.html()
    def html(self):
        return """
        <!DOCTYPE html>
        <html lang="ar">
        <head>
            <meta charset="UTF-8">
            <title>SIN.COM</title>
           
            <style>
                body {{
                    font-family: Arial, sans-serif;
                    background-color: #f4f4f4;
                    color: #333;
                    text-align: center;
                    padding: 50px;
                }}
                input[type="text"], input[type="submit"] {{
                    padding: 10px;
                    margin: 10px;
                }}
            </style>
        </head>
        <body>
        <center>
        <hr>
        <mark> <a href="https://t.me/omerislamaker">Devoloper:OMER ABO AKER</a></mark>
        <hr>
            <h1>اسال اي سوال في بالك ؟</h1>
            <form method="post" action="send">
                <input type="text" name="email">
                <input type="submit" value="اضغط هنا لارسال الرسالة واستلام الرد">
            </form>
        </center>         
        </body>
        </html>
                """
    @cherrypy.expose
    @cherrypy.tools.allow(methods=['POST'])
    def send(self, email):
    	url = "http://pass-gpt.nowtechai.com/api/v1/pass"

    	payload = json.dumps({
  "contents": [
    {
      "role": "system",
      "content": "You are All bot, a large language model trained by ChatGPT."
    },
    {
      "role": "user",
      "content": email,
    }
  ]
})

    	headers = {
  'User-Agent': "Ktor client",
  'Connection': "Keep-Alive",
  'Accept': "application/json",
  'Accept-Encoding': "gzip",
  'Content-Type': "application/json",

}

    	r= requests.post(url, data=payload, headers=headers).text
    	i=r.split('content')
    	h=0
    	y=len(i)

    	text=''
    	for j in range(0,y):
    		z=r.split('"content":"')[j].split('"')[0].split('data:{')[0]
    		text+=z
    		h+=1
    		if int(h)==int(y):
    			return text
    def result(self, text):
        return f"""
       <!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>a result</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 20px;
            background-color: #f4f4f4;
        }
        .container {
            max-width: 800px;
            margin: auto;
            background: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h1 {
            text-align: center;
            color: #333;
        }
        .result {
            margin-top: 20px;
            padding: 15px;
            border: 1px solid #ccc;
            border-radius: 5px;
            background-color: #fafafa;
        }
        .footer {
            text-align: center;
            margin-top: 30px;
            font-size: 0.9em;
            color: #777;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>The result of the request</h1>
        <div class="result">
            <p>{text}</p>
        <div class="footer">
            <p></p>
        </div>
    </div>
</body>
</html>
        """
if __name__ == '__main__':
    cherrypy.quickstart(Sin())
