.baseUri("https://postman-echo.com")
.body("some data")

                .when()
                .post("/post")

                .then()
                .statusCode(200)
                .body()