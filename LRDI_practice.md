# LRDI practice

## IMPORTANT

![image](https://github.com/user-attachments/assets/2ebe6cdc-15a8-4bf4-94d2-f55d1ab51ae1)
![image](https://github.com/user-attachments/assets/1785fb93-8391-45ae-93be-dce432d5eab5)
![image](https://github.com/user-attachments/assets/e14e996a-15a9-41a2-9780-4621b71b5e00)

## Data Arrangements(1)

![image](https://github.com/user-attachments/assets/ac4bb240-44c7-49f1-a8cf-9c18d7632490)

* [Question]

![image](https://github.com/user-attachments/assets/40247287-a172-4dc7-a988-bf130b4d551d)
![image](https://github.com/user-attachments/assets/21b01532-6eda-4b5e-8f12-259e3a19888d)

* Arun interior avg -> 4.5
* Arun interior accross '2' cars -> 4.5 * 2 -> 9.
* It is important to arrange the data.

![image](https://github.com/user-attachments/assets/af878947-aef2-4e61-b150-0b9722d32e64)

* Maruti interior avg accross '4' people -> 4.25
* Maruti interior accross '4' people -> sum -> 4.25 * 4 -> 17.
* Maruti pickup avg accross '4' people -> 5
* Maruti pickup accross '4' people -> sum -> 5 * 4 -> 20.
* Maruti mileage avg accross '4' people -> 7
* Maruti mileage accross '4' people -> sum -> 7 * 4 -> 28.
* Tata interior -> 6.5 * 4 -> 26
* Tata pickup -> 5.25 * 4 -> 21
* Tata mileage -> 4 * 4 -> 16

![image](https://github.com/user-attachments/assets/d419e765-9f37-492c-ac53-36549950a222)

* Maruti interior:-
* Min -> 2, Avg -> 4.25, Max -> 6.
* We need **4** values from the '4' friends for Maruti interior. We know '2' already which are '2 and 6'.
* The sum of the '4' values is '17'.
* Left -> 17 - (2 + 6) -> 9.
* We gpt '2' combinations which are '4 and 5' and '3 and 6'.

![image](https://github.com/user-attachments/assets/db78eda1-f60e-4446-bf2f-b6c01508b7b0)

* Tata interior:-
* Min -> 5, Avg -> 6.5, Max -> 8.
* We need **4** values from the '4' friends for Tata interior. We know '2' already which are '5 and 8'.
* The sum of the '4' values is '26'.
* Left -> 26 - (5 + 8) -> 13.
* We gpt '2' combinations which are '7 and 6' and '5 and 8'.

![image](https://github.com/user-attachments/assets/799d0ce9-a4c5-4733-a8a3-95a0c73a6c00)

* Maruti Pickup

![image](https://github.com/user-attachments/assets/232760b3-1a92-4607-8c49-c24fa42162be)

* Tata Pickup

![image](https://github.com/user-attachments/assets/d2ff2f13-6246-49b2-832f-a3afb40dc4dc)

* Mileage.
* We have to put these data now in the table.
* Attacking point -> Minimum/Maximum.

![image](https://github.com/user-attachments/assets/6b6974b0-62a8-480f-8a11-a529c68946f3)

* Chandu:-
* Maruti max -> 2, Maruti min -> 6.
* Maruti interior -> 2
* Chandu avg of interior -> 4
* Chandu sum of interior -> 8
* 2 + 6 -> 8.
* Chandu interior of tata -> 6.

![image](https://github.com/user-attachments/assets/af4a3149-845a-47b5-9494-eec74b027a58)
![image](https://github.com/user-attachments/assets/56482e14-45b5-4159-ae4c-5135a389d539)
![image](https://github.com/user-attachments/assets/b12386a6-9b97-460a-9932-69cbfd1d278a)
![image](https://github.com/user-attachments/assets/d320544c-442e-4b2e-9de5-d3e9bd79a60f)

* A's interior sum -> 9.
* 5 + 4 -> 9.  

![image](https://github.com/user-attachments/assets/7703162e-36d6-4ca9-b3fe-3707e9b9d60a)

* B's interior sum -> 13.
* D's interior sum -> 13.
* This is a **problem**. We cannot **differentiate**.
* 5 + 8 -> 13
* 6 + 7 -> 13.

![image](https://github.com/user-attachments/assets/b2a017c6-cc80-4df3-bdfb-c9858ef8070d)

* A's mileage sum -> 5.5 * 2 -> 11.
* 7 + 4 -> 11.
* 8 + 3 -> 11.
* 6 + 5 -> 11.
* As we are getting more cases that's why we are thinking more deep/deeply.
* A has to give a rating of '8' to maruti. There is no '8' in interior or pickup. '8' should come in **mileage**.

![image](https://github.com/user-attachments/assets/17b0970a-3070-417b-a063-9ddbee80ca10)

* B's mileage sum -> 4.5 * 2 -> 9.
* In tata, for '4' we need '5' in maruti which is not there.
* In tata, for '7' we need '2' in maruti which is not there.
* In tata, for '2' we need '7' in maruti which is there.
* 7 + 2 -> 9.

![image](https://github.com/user-attachments/assets/d2e38ecf-4696-4669-aa10-60f454c249ae)

* In maruti, '7 and 8' are used/alloted. '6 and 7' are left.
* In tata, '2 and 3' are used/alloted. '4 and 7' are left.
* C's mileage sum -> 5 * 2 -> 10.
* 4 + 6 -> 10.

![image](https://github.com/user-attachments/assets/7effc148-27a1-499b-a507-35e3a45846f1)
![image](https://github.com/user-attachments/assets/ec2ecd56-3183-42bb-9042-498a991d9ebd)
![image](https://github.com/user-attachments/assets/1c45807f-a943-4fd1-a847-26934e04918b)

* D's mileage sum -> 7 * 2 -> 14.
* 7 + 7 -> 14.

![image](https://github.com/user-attachments/assets/bdd0f7fa-f666-4441-96e4-505f71880475)
![image](https://github.com/user-attachments/assets/56cf8ab6-97af-4a80-bfec-4357b4d20cfd)

* We are using table '2'.
* A's rating to tata -> 3 and 6. We see '3' in mileage but no '6'. So '6' is in pickup.
* A's pickup sum -> 6.5 * 2 -> 13.
* 13 - 6 -> 7.

![image](https://github.com/user-attachments/assets/45432dd3-390d-4622-9b20-6f640819353f)

* B's rating to maruti -> 4 and 7. We see '7' in mileage but no '4'. So '4' is in pickup.
* B's pickup sum -> 6 * 2 -> 12.
* 12 - 4 -> 8.

* C's rating to tata -> 4 and 6. We already have both.
* C's rating to maruti -> 2 and 6. We already have both.
* Will check later.

![image](https://github.com/user-attachments/assets/1c563223-7585-450c-a016-20120a7576f0)

* D's rating to maruti -> 5 and 7. We already have both.
* D's rating to tata -> 2 and 8. We see '8' in mileage but no '2'. So '2' is in pickup.
* D's pickup sum -> 4 * 2 -> 8.
* 8 - 2 -> 6.

![image](https://github.com/user-attachments/assets/ffe1f552-842e-447e-9182-755720b363b5)
![image](https://github.com/user-attachments/assets/34423f8d-6423-4899-8a3b-20fa7f5e01d4)
![image](https://github.com/user-attachments/assets/629fadad-89e6-4fa9-bbee-86825257ef09)

* C's pickup sum -> 4 * 2 -> 8.
* 8 - 3 -> 5.
* B's rating to maruti -> 4 and 7 -> they are in range. 
* B's rating to tata -> 2 and 8 -> they are in range.

![image](https://github.com/user-attachments/assets/07e1ed22-18bd-409f-af85-fd537ed8cc64)
![image](https://github.com/user-attachments/assets/508f183c-4df4-4edd-b83a-afecbcc7efc6)

* D's rating to maruti -> 5 and 7 -> We don't have '5'. We have 6,7 and '6 or 5'. We will keep '5'. 
* D's rating to tata -> 2 and 8 -> they are in range.
* D's interior sum -> 6.5 * 2 -> 13.
* 13 - 5 -> 8.
* We will keep '8' in interior of tata. 

![image](https://github.com/user-attachments/assets/db92592f-91a9-4729-ad10-a04e04921190)
![image](https://github.com/user-attachments/assets/5ce5c18c-0ec7-4308-a824-f9937ce822fa)
![image](https://github.com/user-attachments/assets/a9253c67-4181-4665-9c80-e128f3141472)

* Maruti interior -> 2,6,4,5 -> keep '6'.
* B's interior sum -> 6.5 * 2 -> 13.
* 13 - 6 -> 7.
* We will keep '7' in interior of tata. 

![image](https://github.com/user-attachments/assets/bb0ac4d5-b176-4877-9a53-73ce640b7ae2)

* Answer -> 4. [1] [Answer] [Solution]
* Answer -> 5. [2] [Answer] [Solution]
* Answer -> 7. [3] [Answer] [Solution]
* B's rating of mileage to TATA -> 2
* D's rating of pickup to maruti -> 6
* Positive diff -> 6 - 2 -> 4.
* Answer -> 4. [4] [Answer] [Solution]

![image](https://github.com/user-attachments/assets/1680d518-ccf3-4856-9178-67e1086977d0)
![image](https://github.com/user-attachments/assets/c9b45050-e751-47f6-9919-d4f860c609fc)
![image](https://github.com/user-attachments/assets/842dab58-0740-458b-87ad-c404f6750698)

* [Question]

![image](https://github.com/user-attachments/assets/dd4c0508-7ff7-4948-a2b5-3afb916919e2)

* Assem loss in maths -> 40% of 12a -> 4.8a
* Assem loss in social studies -> 40% of 20a -> 8a

![image](https://github.com/user-attachments/assets/7534d124-bc83-4aa7-b591-fc45054fa312)
![image](https://github.com/user-attachments/assets/c3815967-d82b-4ad5-8422-514a15495855)
![image](https://github.com/user-attachments/assets/1593e2fa-756a-48d4-99f4-9c6adeb0e593)

* Total -> Scored + lost.

![image](https://github.com/user-attachments/assets/09b20ab5-9845-4553-ad58-a581ac4f167d)

* As : Ay : Sa -> 5 : 2 : 1
* a = 5, b = 2, c = 1
* Sa -> 100 * 5 -> 500.
* Ay -> 100 * 2 -> 200.
* As -> 100 * 1 -> 100.

![image](https://github.com/user-attachments/assets/c5d3b72f-a479-4b94-bbec-4981338c48e3)
![image](https://github.com/user-attachments/assets/65c8e769-87f8-427b-b276-19f1696a6ca8)

* Answer -> 20%. [1] [Answer] [Solution]

![image](https://github.com/user-attachments/assets/fe4e63d5-176d-403c-af54-09b4949394d9)

* Ayan lost in science -> 10% of 9b -> 0.9b

![image](https://github.com/user-attachments/assets/241b66bc-227b-4a95-bcfe-7403811cae0c)
![image](https://github.com/user-attachments/assets/a00d2160-9492-4e5d-81de-7350863d9f2b)

* Answer -> 0.6%. [2] [Answer] [Solution]

![image](https://github.com/user-attachments/assets/379e43db-ea5d-4a67-9507-846197a24626)

* Atleast -> minimum/minimize.
* 12 * 1.5 -> 18
* 25 * 1.5 -> 37.5

![image](https://github.com/user-attachments/assets/98ca8690-cb96-4fa8-9286-51f19c6067b7)
![image](https://github.com/user-attachments/assets/c6977ca9-0f05-455a-8970-0567981c1c55)
![image](https://github.com/user-attachments/assets/5e8919b5-02f4-4cf8-9682-68507c53d509)

* Answer -> 37.5%. [3] [Answer] [Solution]

![image](https://github.com/user-attachments/assets/353cd288-8bf5-49c3-9580-8b20584697d9)

* Ayan lost marks in eng due to Q -> 36% of 6b = 45
* b = 125/6
* cannot be more than -> maximum/maximize.
* Samantha lost marks in maths due to T -> 20% of 4c -> 

![image](https://github.com/user-attachments/assets/b54a3f00-bbb3-4586-852e-20b5ec23ef96)
![image](https://github.com/user-attachments/assets/264b7fe1-e5b2-4423-9aa8-986620e69867)

* Answer -> 40. [4] [Answer] [Solution]

## Alphanumeric Puzzles(2)

![image](https://github.com/user-attachments/assets/95724c23-ff9c-4109-86dc-1d5b8bb7909a)

* Rule 1 -> Same alphabet -> Same number
* Rule 1 -> Same alphabet -> Same number

* If we add '2' nos then the max. carry forward is '1' which is from, 9 + 9 -> 18 -> carry of '1'.
* There will be either carry forward of '1' or no carry forward at all.

![image](https://github.com/user-attachments/assets/0549f5fb-e262-4bf6-8456-b018966c8613)
![image](https://github.com/user-attachments/assets/0c607a08-c81d-4459-b760-92485ab7dea4)
![image](https://github.com/user-attachments/assets/f4f5700e-6407-4683-9916-81c671017585)

* [Question]
* start from 10mins.



































