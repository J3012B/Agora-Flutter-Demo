# Agora Group Video Call in Flutter

This project is an example for how to implement the [Agora SDK](https://www.googleadservices.com/pagead/aclk?sa=L&ai=CIQyvlcG-YYSrAuyHrtoPicarsA2t4eTvY7Onkp-HDtXhzi4IABABILlUYOmCgIDUDaABsPW-vQPIAQHIA9ggqgRWT9AXcf9fYxI5YNp9haeM6jm9H_SM8wtt12SQP4sqEGHjj-qT61IBkIqsjUF1dCACvsv3MmjZ7iSSR7PTHlJGqckQDd9gIda6gk1k1Uv3nyLzIS1rqhTABLjkq5_IA4AFkE6gBmaAB7iKwUKIBwGQBwGoB6a-G6gHuZqxAqgH89EbqAfu0huoB_-csQKoB8rcG7AIAdIIBRACIIQBmgkYaHR0cHM6Ly93d3cuYWdvcmEuaW8vZW4vsQmOhNHBew_Am7kJjoTRwXsPwJv4CQGYCwGqDAIIAbgMAcgUiZ6btp-pjqJt0BUBmBYB-BYBgBcBkhcIEgYIARADGFA&ae=2&ved=2ahUKEwjf5sqqj-_0AhW763MBHbn0A8kQ0Qx6BAgCEAE&dct=1&dblrd=1&sival=AF15MECTQslMoJJIe86HvNzC9yaCsTv1Jmy5t5NccY1ESPYwPLGi4RQY8n4rrxo03NOU_Ov5gQmhbpxYQBQCmpGZT-1on7xZbBAYTwq5WVcziebYBg6vK_jfichFAir-rdw0-QLvCPbEWJ8HtLwQxLFQ6TtcLLCoPmvuxF587cAMtqB6580w2Xo&sig=AOD64_3KZTLPtzj4e8W8OwG0zqe6xpPUBQ&adurl=https://www.agora.io/en/%3Futm_source%3Dgoogle%26utm_medium%3Dcpc%26utm_keyword%3Dagora%26utm_device%3Dc%26utm_campaign%3Dbrand-india%26utm_content%3D) in [Flutter](https://flutter.dev/docs).
It showcases how to create an Agora channel, how to join it and supports features like switching the camera and toggling the microphone.
Multiple remote users can join the channel simultaneously.

![Screenshot_2021-12-19-13-17-16-00_273afa6be60c88abcd0b5639793f0c97](https://user-images.githubusercontent.com/23200445/146667596-8c46a96d-7708-40a3-bccc-79ff6cadcf29.jpg)

![Screenshot_2021-12-19-13-17-41-18_273afa6be60c88abcd0b5639793f0c97](https://user-images.githubusercontent.com/23200445/146667606-72d86de5-51ed-4e46-a303-1f27248d6389.jpg)



## Instructions

To make the project work, please specify an Agora App ID and an Agora access token you can both retrieve by creating an Agora account and a project within their console.
You have to specify those within `CallPage.dart` on `_engine.joinChannel(...)`.
