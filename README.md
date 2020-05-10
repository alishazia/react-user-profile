### Task to be done

- You are given a random user api which will return an array of type user for which the format is given below
```json
{
  "results": [
    {
      "gender": "male",
      "name": {
        "title": "mr",
        "first": "brad",
        "last": "gibson"
      },
      "location": {
        "street": "9278 new road",
        "city": "kilcoole",
        "state": "waterford",
        "postcode": "93027",
        "coordinates": {
          "latitude": "20.9267",
          "longitude": "-7.9310"
        },
        "timezone": {
          "offset": "-3:30",
          "description": "Newfoundland"
        }
      },
      "email": "brad.gibson@example.com",
      "login": {
        "uuid": "155e77ee-ba6d-486f-95ce-0e0c0fb4b919",
        "username": "silverswan131",
        "password": "firewall",
        "salt": "TQA1Gz7x",
        "md5": "dc523cb313b63dfe5be2140b0c05b3bc",
        "sha1": "7a4aa07d1bedcc6bcf4b7f8856643492c191540d",
        "sha256": "74364e96174afa7d17ee52dd2c9c7a4651fe1254f471a78bda0190135dcd3480"
      },
      "dob": {
        "date": "1993-07-20T09:44:18.674Z",
        "age": 26
      },
      "registered": {
        "date": "2002-05-21T10:59:49.966Z",
        "age": 17
      },
      "phone": "011-962-7516",
      "cell": "081-454-0666",
      "id": {
        "name": "PPS",
        "value": "0390511T"
      },
      "picture": {
        "large": "https://randomuser.me/api/portraits/men/75.jpg",
        "medium": "https://randomuser.me/api/portraits/med/men/75.jpg",
        "thumbnail": "https://randomuser.me/api/portraits/thumb/men/75.jpg"
      },
      "nat": "IE"
    }
  ],
  "info": {
    "seed": "fea8be3e64777240",
    "results": 1,
    "page": 1,
    "version": "1.3"
  }
}
```

** The result array will have multiple users depending on the query param `results` . We can give the query parameter to fetch the no of users of our choice **

- I want to be able to see the users in a list of cards with primary information. Primary information will include name, gender, email, age and a thumbnail photo of the user
- When I click a card, I should be taken to a page with all the details for the user.
- Whenever the api doesn't respond, I should be notified of the same
> The api documentation can be found at [Random User Documentation](https://randomuser.me/documentation)

#### Checklist
- [ ] Users are displayed as cards
- [ ] Primary info is present on the card
- [ ] Clicking the card will take to a details page
- [ ] Details page contains all the info of the user presentable layout
- [ ] Aesthetic looks will fetch extra marks
- [ ] Code ethics and formatting should be followed at the times
- [ ] Any extra feature like search sort and filter would be applaudable
- [ ] Modular and reusable code is a **must**
- [ ] Optionally on the user details page, I can click the location and get directions to the user address
- [ ] Choice of libraries matters. Dont use a library if not required
- [ ] Finally from the user details page, I should be able to download a pdf with all the user info (Optional).

Good Luck to me :smiley: :+1: :heart_eyes: