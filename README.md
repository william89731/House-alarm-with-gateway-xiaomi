# House-alarm-with-gateway-xiaomi (mi control hub)

I revived the xiaomi gateway using [home assistant](https://www.home-assistant.io/), [node red](https://nodered.org/) and [mi home mod (vevs)](https://pdalife.com/mi-home-android-a35796.html)

# Step 1:  ip and token

After you have installed mi home mod and associated your gateway, in the app go to "more info","network info",  get ip and token

![immagine](https://user-images.githubusercontent.com/68069659/103764747-57f65580-501c-11eb-9bde-b3d018505274.png)


# step 2: home assistant

search [xiaomi miio](https://www.home-assistant.io/integrations/xiaomi_miio) integration and add gateway (ip and token required)

![immagine](https://user-images.githubusercontent.com/68069659/103765717-f1723700-501d-11eb-9310-da08a19dd987.png)

I added a custom [button card](https://github.com/custom-cards/button-card) for manual control

![20210106_192639](https://user-images.githubusercontent.com/68069659/103807306-83963180-5056-11eb-84e3-81a0186a2bb7.gif)

code [here[(https://github.com/william89731/House-alarm-with-gatexay-xiaomi/blob/main/button%20card%20alarm.txt)



# step 3: node red

I have created flows for automatic and manual switching of the alarm. enjoy!!

![immagine](https://user-images.githubusercontent.com/68069659/103811192-d672e780-505c-11eb-8701-8a5e93f45282.png)

code [here](https://github.com/william89731/House-alarm-with-gatexay-xiaomi/blob/main/flows%20alarm.txt)















