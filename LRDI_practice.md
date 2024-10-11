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

![image](https://github.com/user-attachments/assets/9a4c7ee2-863f-40fd-801a-4aa9231c5f0e)

* Same alphabet -> Same value. [Concept] [Logic] [**VERY IMPORTANT**]
* Different alphabet -> Different value. [Concept] [Logic] [**VERY IMPORTANT**]

![image](https://github.com/user-attachments/assets/7b17b06a-4436-42eb-b1b7-12ff3220060f)
![image](https://github.com/user-attachments/assets/f87899a1-3111-42c6-b2bb-41d25fe19640)
![image](https://github.com/user-attachments/assets/0cc9e070-6a31-45f4-8e21-d9839ad62989)

* 3 * 4 -> 12.
* E -> 4.
* 1 + 3 * D = E -> 1 + 3 * D = 4 -> D = 3/3 -> D = 1.
* D -> 1.
* 3C = 1.
* 3 * 7 -> 21 -> '2' is carry and we write down '1'.
* C -> 7.
* 2 + 3B = 7 -> 3B -> 5
* 3 * 5 -> 15 -> '1' is carry and we write down '5'.
* B -> 5.
* 1 + 3A = 5 -> 3A -> 4
* 3 * 8 -> 24 -> '2' is carry and we write down '4'.
* A -> 8.
* 2 * 3 + 2 -> 8.

![image](https://github.com/user-attachments/assets/51fbe6f6-ca00-4910-b861-41660f27022a)

* [Question]

![image](https://github.com/user-attachments/assets/04695bfa-9780-41c9-a464-131f7b71d7d9)

* 3 * 5 + 2 -> 17 -> '1' is carry and we put down '7'.

![image](https://github.com/user-attachments/assets/280e214e-c660-4f62-977a-cf66ea09b5fc)
![image](https://github.com/user-attachments/assets/acc70fd3-8775-4170-bac4-69d17eb35287)
![image](https://github.com/user-attachments/assets/b41fd992-4178-4c36-9c92-3a7698ee607a)
![image](https://github.com/user-attachments/assets/0e90451b-ad94-4d1f-a8fb-6f6672331a15)

* [Question]
* A -> 1 or 2.
* 3 * 4 -> 12 -> It will become a '5' digit no. which we don't want. 'A' value can't me more than '2'.
* 4 * something -> Even no. only -> Can't be '1'.
* 4 * D -> 2.
* A -> 2.
* 4D -> 2
* 4 * 3 -> 12 -> '1' is carry and we put down '2'.
* 4 * 8 -> 32 -> '3' is carry and we put down '2'.
* D -> 3 or 8.

![image](https://github.com/user-attachments/assets/6fa2ef7c-30bb-4907-95b5-e9d92def08b8)
![image](https://github.com/user-attachments/assets/7a90d7e9-e257-4802-b2a4-1f299a15c490)

* 4 * A -> D
* 4 * 2 -> 8.
* 4 * 2  + 1 -> 9.
* 'D' can be '8' or max. to max. can be '9' with carry from previous. So 'D = 3' is not possible. 'D' has to be '8'.
* D -> 8.
* Carry of '3' to 'C'.
* As we are adding '3' to 'C' so we can say that 'B' is **odd**.
* B -> odd.
* 4B -> C.
* There was no carry forward as we got 'D = 8' only. So, 'B' can be either '0 or 1 or 2', it cannot be more that '2' like in 'A'.
* As we have already used '2' in 'A' and we cannot repeat it. As 'B' is odd so 'B = 1'.

![image](https://github.com/user-attachments/assets/0b4c0397-d694-40ae-b45f-0106c101a99a)

* B -> 1. [Answer] [Solution] [**VERY IMPORTANT**] [Practice]
* 4C + 3 -> 1
* 4 * 2 -> 8
* 8 + 3 -> 11 -> '1' is carry and we put down '1'.
* 4 * 7 -> 28
* 28 + 3 -> 31 -> '3' is carry and we put down '1'.
* C -> 2 or 7.
* Have already used '2'. So,
* C -> 7.

![image](https://github.com/user-attachments/assets/3160a8f0-45b8-4fbe-b25e-75a461613584)
![image](https://github.com/user-attachments/assets/32a639f2-da57-4929-8a0e-340f7f3c9a66)

* Complete.[Answer] [Solution] [**VERY IMPORTANT**] [Practice]

![image](https://github.com/user-attachments/assets/3b201539-42d1-4b61-88c0-ab87072301cb)
![image](https://github.com/user-attachments/assets/e0276d37-7940-4f30-90e4-9f80293d7d2e)

* EN + EN -> 00 -> Double '0'. [Not for CAT]

![image](https://github.com/user-attachments/assets/91415089-f7eb-4d70-ac5e-b22bdec39017)

* [Question]

![image](https://github.com/user-attachments/assets/f5bf5d5c-8951-40a9-a5c2-e6604b7699cc)
![image](https://github.com/user-attachments/assets/19f774c4-b79c-4d10-bb57-30848a86685c)

* [Question]

![image](https://github.com/user-attachments/assets/96e56f8b-4572-4e11-b748-0c969de7cb50)

* Max. carry forward is '1'.
* c = d + 1.
* a + b = d -> without carry forward.
* D + E = C -> d + e = d + 1 -> e = 1.
* E -> 1. [No carry forward]
* f + f = b -> 2f = b.
* b -> Even number -> Adding of '2' nos. is even only.
* If 'B = 2' case:
* A = 3 -> because '1 and 2' are taken.

![image](https://github.com/user-attachments/assets/7c875b5d-4ddb-4ce9-9811-dab6248f763a)
![image](https://github.com/user-attachments/assets/c7d55a72-5c91-4e3c-9c5a-b3183c31f1af)

* A + B = D -> 2 + 3 -> 5.
* D = 5.
* Case **1** -> This case is **not possible** because 'F' has to be either '2 or 6' for 'B = 2' but both '2 and 6' are taken already.
* Case **2** -> This case is also **not possible** similar to case **1**.

![image](https://github.com/user-attachments/assets/6cc4d0f7-f4e3-4bde-b028-be6d97c2c934)

* We need 'F = 2  or 7' for 'B = 4 and A = 2'.

![image](https://github.com/user-attachments/assets/80aea901-c2e4-47aa-bdea-26f0e0a36b7c)
![image](https://github.com/user-attachments/assets/892c1ca4-7f09-42ad-8f13-c1d094cf0422)

* G + H + 1 -> 8.
* 8 + 9 + 1 -> 18 -> '1' is carry and '8' we put down.
* '8' is already taken in 'c'. So this is also **not possible**.

![image](https://github.com/user-attachments/assets/5363a456-b33b-41d8-bc40-200246ea96ee)
![image](https://github.com/user-attachments/assets/d9233532-7a9c-4042-ab5f-0be33d9c2269)

* Nos. left -> 0,3,4,9.
* g + h + 1 -> 8.
* 3 + 4 + 1 -> 8.
* G -> 3/4.
* H -> 4/3
* 6 + 7 -> H.
* H -> 13 -> '1' is carry and '3' we put down.
* H -> 3
* G -> 4.

![image](https://github.com/user-attachments/assets/54782302-f963-4dcc-becd-2212cd2dc080)
![image](https://github.com/user-attachments/assets/2f0248f9-4900-4331-bc7b-a37baad565f3)
![image](https://github.com/user-attachments/assets/1462f4eb-08bf-4ae4-a102-61be0b50b54e)

* Answer -> 4. [1] [Answer] [Solution] [**VERY IMPORTANT**] [Practice]
* Answer -> 3. [2] [Answer] [Solution] [**VERY IMPORTANT**] [Practice]
* Answer -> 2. [3] [Answer] [Solution] [**VERY IMPORTANT**] [Practice]
* Answer -> 7. [4] [Answer] [Solution] [**VERY IMPORTANT**] [Practice]
* Answer -> 1. [5] [Answer] [Solution] [**VERY IMPORTANT**] [Practice]
* Obtained by calculator -> 4
* Shown by calculator -> 7

![image](https://github.com/user-attachments/assets/655a5f08-8322-4413-bae3-085795ba2ed0)
![image](https://github.com/user-attachments/assets/42bddda1-53ed-467c-aa17-b58083569d28)

* [Question]

![image](https://github.com/user-attachments/assets/1303d383-fed6-45e9-97a3-57999fd2972b)

* P6 -> Sh/L
* P1/P3 -> Sh/L
* P10 -> R/G
* P7 -> R/G
* P8 -> H
* We know 'H' is closer to 'G'.
* P10 -> R
* P7 -> G

![image](https://github.com/user-attachments/assets/70e456e5-2ce5-4a08-934e-74d162268cd0)
![image](https://github.com/user-attachments/assets/6525433b-52a9-4272-8e3f-526d32ad3835)
![image](https://github.com/user-attachments/assets/92c1329e-3b93-4942-91e4-714d2321f7ba)

* Example.
* P4 -> D.
* P6 -> not L -> Sh.

![image](https://github.com/user-attachments/assets/73263c5f-d002-4b36-88b7-295889c2d5eb)
![image](https://github.com/user-attachments/assets/78977162-6325-48ea-a9db-e68c6891efdf)
![image](https://github.com/user-attachments/assets/1e61bbc2-75c5-456b-9afd-8cfb0393d4ee)

## Data Arrangements(3)

![image](https://github.com/user-attachments/assets/b3fd5785-baf6-42ff-9557-5b7c6de25847)
![image](https://github.com/user-attachments/assets/3932e291-8c8a-48ca-91e8-3bf8a401fa01)
![image](https://github.com/user-attachments/assets/bcf97753-3902-4aa4-8630-8952d5a31b14)

* [Question]

![image](https://github.com/user-attachments/assets/ac05c470-2d2d-4a24-9ea9-b80f145de91b)
![image](https://github.com/user-attachments/assets/14a2d4fb-738e-479f-aac7-a447fc8ae399)
![image](https://github.com/user-attachments/assets/e17cb067-407e-4b84-a128-5cc6f168f954)

* Jayanth's surname -> not 'gupta' or 'sharma'.

![image](https://github.com/user-attachments/assets/ea86c0da-4131-4ecf-bc79-16752ae5327f)

* Parvindar's surname is either gupta' or 'sharma' as they also taught on a monday.

![image](https://github.com/user-attachments/assets/9ebb44ab-2d2b-43be-8aa9-21533347d2a5)
![image](https://github.com/user-attachments/assets/24434bd9-e449-4554-85b8-deebe4e7b258)

* '1' facult can teach for a max. of '6hrs'. Parvindar taught for all '6' days of the week so he taught for '1hr' every day.
* Operation management(OM).
* 6hrs -> 3days -> 3 * 2 = 6 -> 2hrs every day.

![image](https://github.com/user-attachments/assets/538c7f84-d630-4d38-b314-a65a52a34e57)

* 6hrs -> 1 + 2 + 3.

![image](https://github.com/user-attachments/assets/b077063f-7830-41ca-b588-6d0f4b04fe89)

* Wed + Fri + Sat -> avg of 8hrs -> 8 * 3 -> 24hrs.
* 24 -> 7 + 8 + 9 'OR' 8 + 7 + 9.
* Sat -> 9hrs fixed.
* Mon -> 3 * 1 -> 3hrs fixed.

![image](https://github.com/user-attachments/assets/8b067228-6d71-41ab-bd02-9975626ec2ee)

* Max -> 9
* Min -> 3
* 3 to 9 distinct numbers -> We need '6' nos. because of 6 days.
* '6' faculty taught for '6hrs' each -> 6 * 6 -> 36hrs total.
* Used -> 7 + 8 + 9 + 3 -> 27
* Left -> 36 - 27 -> 9hrs.
* Tues + Thus -> 9hrs.
* Tues > Thus [Point '9']
* 5 + 4 -> 9.
* 6 + 3 -> 9 -> '3' is already occupied so we cannnot use that. 
* 7 + 2 -> 9 -> '7' is already occupied so we cannnot use that. 
* 8 + 1 -> 9 -> '8' is already occupied so we cannnot use that. 

![image](https://github.com/user-attachments/assets/97d664a5-8cb3-48ff-aca6-14e74a2f94d4)

* Tues -> 5.
* Thus -> 4.
* Wed -> 7 or 8.
* Fri -> 7 or 8.
* They can shuffle between '7 and 8hrs'.

![image](https://github.com/user-attachments/assets/0fc1c1dd-3b17-47fd-9cff-530a881b9ad9)
![image](https://github.com/user-attachments/assets/3ab216dd-ace6-4747-b419-0c5c281b601a)

* Marketing faculty -> Wed + Fri + Sat -> 6hrs
* Wed - Fri -> 2.
* 1/3 or 3/1.
* Marketing faculty taught for '2hrs' on friday. 
* 5days for 6hrs -> 1 + 1 + 1 + 1 + 2 -> 6hrs.

![image](https://github.com/user-attachments/assets/5b09fb43-87ea-414d-ba5c-479e4619aa32)
![image](https://github.com/user-attachments/assets/7d09a7f1-4e71-4ada-b25e-905cf38f028d)
![image](https://github.com/user-attachments/assets/ef8847c1-0016-4bd9-9cef-26c1fbf0b77d)
![image](https://github.com/user-attachments/assets/013b413a-496e-47ea-83dc-e2805fd0c5b8)
![image](https://github.com/user-attachments/assets/5a42a983-6d99-4d52-84a3-8257b7c511aa)

* Keshav -> on '4' days.
* Min. no. of days -> For '2' days with '3hrs' each.

![image](https://github.com/user-attachments/assets/8cf7fa6a-15ca-437f-acfc-c47cbeba32ac)
![image](https://github.com/user-attachments/assets/354b747b-5398-4586-9c9c-3196c0e1145b)
![image](https://github.com/user-attachments/assets/e5c65fa7-8647-4603-81fb-e28291fb8946)

* Jayant -> 6hrs -> We got '1 + 2 = 3hrs' -> We are left with '3hrs' for 2days -> '1 + 2 = 3hrs'.
* Jayant cannot go with jaiswal as stated in point '13', starting letter of name and surname cannot be the same.

![image](https://github.com/user-attachments/assets/ecf9202b-caa6-45af-a92c-cf5cabd1f7bb)

* Answer -> 4. [1] [Answer] [Solution] [**VERY IMPORTANT**] [Practice]
* Answer -> CBD -> option **D**. [3] [Answer] [Solution] [**VERY IMPORTANT**] [Practice]

![image](https://github.com/user-attachments/assets/c2da8c3f-84f2-4150-8f15-463e61f30fff)

* Anand -> marketing -> friday -> 2hrs.

![image](https://github.com/user-attachments/assets/bc477598-8023-443e-b63e-530915e32331)

* Thus -> 4hrs -> 1hr by Jay, 1hr by Par, 1hr by kesh.
* That's why we cannot put neha in thusday.
* Thus and monday are done.
* Neha  -> tues, wed, fri -> 2hrs every day.
* Fri -> 2 + 2 + 3 + 1 -> 8hrs
* Wed -> 7hrs.

![image](https://github.com/user-attachments/assets/05a401d4-f1da-4f4f-9f96-ccf70b477836)

* Tues -> 5hrs -> 2 + 3  * 1 -> 5hrs.
* Wed -> 7hrs -> 2 + 1 + 2 -> 5hrs -> 7 - 5 -> 2hrs left -> anand '1hr' and keshav '1hr' -> 5 + 2 * 1 -> 7hrs.

![image](https://github.com/user-attachments/assets/e2181045-59f1-4442-a0b6-6e133d60592b)

* Sat -> 9hrs -> 3 + 1 + 3 -> 7hrs -> 9 - 7 -> 2hrs left -> keshav '2hrs' -> 7 + 2 -> 9hrs.

![image](https://github.com/user-attachments/assets/46937949-aee6-4507-9a13-eac672849ffd)
![image](https://github.com/user-attachments/assets/9bdd27a6-1e0d-4539-bd34-a68202ced831)
![image](https://github.com/user-attachments/assets/5fceed5f-d2e7-473d-a56b-577599fbf169)
![image](https://github.com/user-attachments/assets/80d259fa-8477-48e2-a392-b826c2cd322a)
![image](https://github.com/user-attachments/assets/04908293-9b6a-4af3-bb54-53cb5ebaf22f)

* Answer -> Tues, wed, fri -> option **B**. [2] [Answer] [Solution] [**VERY IMPORTANT**] [Practice]
* Answer -> 2. [4] [Answer] [Solution] [**VERY IMPORTANT**] [Practice]
* Answer -> option **C**. [5] [Answer] [Solution] [**VERY IMPORTANT**] [Practice]

![image](https://github.com/user-attachments/assets/dcdf580d-38e2-4ac6-b3d5-8a29c13e936e)
![image](https://github.com/user-attachments/assets/1be74875-2f9c-4a76-9781-7adc8ce37b62)
![image](https://github.com/user-attachments/assets/1ddd5f84-25f9-486c-9446-62f3447ead05)

* [Question]

![image](https://github.com/user-attachments/assets/bd8645fe-c3e8-4927-b945-58f93f13a1b6)

* 95000 - 10000 -> 85000

![image](https://github.com/user-attachments/assets/772e6b68-a088-440a-8fdc-15c411a6d00b)

* These guys are not loosing their security deposits.

![image](https://github.com/user-attachments/assets/150ddc62-3819-470c-8582-d77090a5a3ad)
![image](https://github.com/user-attachments/assets/d3a2d10d-ba85-420d-b97f-07df88905dff)

* These guys have lost their security deposits.
* Answer -> 9% -> option **E**. [1] [Answer] [Solution] [**VERY IMPORTANT**] [Practice]

![image](https://github.com/user-attachments/assets/857ec658-e997-4e21-b598-7f7bed7dab93)

* The winner in constituency 'B' has '48750' votes but it is less than the '1/6' votes. He will not lose his security deposits because he is the winner and only the defeated candidates, lose their security deposits.
* 2 to 12 candidates in 'B' -> Got less than '1/6' only -> They lose their security deposits.
* Answer -> 11 -> option **E**. [2] [Answer] [Solution] [**VERY IMPORTANT**] [Practice]

* 1/6 -> 16.66%
* 10% < 16.66%.
* 4th candidate of 'D' gets less than '1/6'.
* 4th to 8th -> gets less than '1/6'.

![image](https://github.com/user-attachments/assets/3c139533-76dd-4c32-8f85-4cffeebeabe2)

* 4th to 8th sum is '35%'. We don't know if it is the winner or not.
* Winner in 'D' got '5%' more than runner up in 'D'.
* 1st + 2nd -> 65%
* 1st -> 35%
* 2nd -> 30% -> 37500.

![image](https://github.com/user-attachments/assets/9b0d1907-2708-4583-afdf-7df0e87b9237)
![image](https://github.com/user-attachments/assets/6d99947d-ce05-43c0-b3b6-01ad9ee11954)

* '2' cases are possible. 

![image](https://github.com/user-attachments/assets/a9fccc9a-629e-4d63-8dc1-abbd01a0468d)
![image](https://github.com/user-attachments/assets/75c9b2aa-99a0-4ef6-aaa6-bdeb19d201b8)

* 65% -> 1/6 of 125K -> ~21K
* 3rd person of 'D' -> 30k.
* 30k > 1/6 -> 30k > 21k.
* both are contradicting each other. So case **1** is rejected.
* Only case **2** is possible.

![image](https://github.com/user-attachments/assets/358aa357-bd22-4c40-bea8-fd3a4272fef0)
![image](https://github.com/user-attachments/assets/2f399ed5-c0af-4a65-90c9-160a1d0ab89e)

* y -> 4/5 -> 0.8x%

![image](https://github.com/user-attachments/assets/e0b4960b-c47b-4464-9c47-49cb3c3a519f)
![image](https://github.com/user-attachments/assets/1d496113-d545-45fb-b651-0ca31cd9d4e0)
![image](https://github.com/user-attachments/assets/3a0f34f1-93ee-4bf5-ae46-85c1ecf12a0f)

* Answer -> 175000 -> option **A**. [3] [Answer] [Solution] [**VERY IMPORTANT**] [Practice]

![image](https://github.com/user-attachments/assets/31f9474f-7d4d-4dc8-9a9a-3f769ed3afe3)

* Divide by '1000' on numerator and denominator.

![image](https://github.com/user-attachments/assets/5c3de3cb-d989-4f98-8430-ad22da2befc6)
![image](https://github.com/user-attachments/assets/c67dd9d1-113d-422f-ba3d-0c1a03aa8a93)

* Choose the option which is just smaller than '24'.
* Answer -> 23.9% -> option **C**. [4] [Answer] [Solution] [**VERY IMPORTANT**] [Practice]

![image](https://github.com/user-attachments/assets/731cc98e-69dc-4de3-9b28-3d2c833e88f4)
![image](https://github.com/user-attachments/assets/e0a4d156-e756-4a3f-b1f6-a653c9c264a7)

* Min. criteria.
* Min. distribution.
* This is the only possibility and no other possibility.

![image](https://github.com/user-attachments/assets/1b662e7d-6b09-4e8d-8066-1d774f61fbe1)

* Answer -> option **A**. [5] [Answer] [Solution] [**VERY IMPORTANT**] [Practice]

## Alphanumeric Puzzles(4)

![image](https://github.com/user-attachments/assets/7ae60e9e-bdcd-4ef9-8339-776e2974d415)
![image](https://github.com/user-attachments/assets/07102eda-1514-431a-92f5-ab388c727970)

* [Question]

![image](https://github.com/user-attachments/assets/51d8e8ee-ecfc-417e-8650-00fb2e91aa73)

* 1st round -> 6 candidates -> '1' president + '5' candidates.
* 2nd and 3rd rounds -> 5 candidates.
* Total points -> 21 + 15 * 2 -> 51.
* 7 -> 2 + 4 + 1.

![image](https://github.com/user-attachments/assets/7688d99b-148a-431b-8183-6c791431fb68)
![image](https://github.com/user-attachments/assets/02e4486c-d638-42e4-8c6d-29b3188dd576)

* Answer -> option **1** -> 2,4,1. [3] [Answer] [Solution] [**VERY IMPORTANT**] [Practice]
* '3' of them have the same points -> x. [Let]
* President value -> p. [Let]
* 7 + 11 + 3x + p = 51 -> 3x + p = 33.

![image](https://github.com/user-attachments/assets/71f7ceaf-42d8-4e53-aed4-b8b92475b3d1)

* if 'p = 3' then 3x = 30 -> x = 10.
* if 'p = 6' then 3x = 27 -> x = 9.

![image](https://github.com/user-attachments/assets/f02da4c8-8a49-48fc-a393-18c9c32118ee)

* case **1** -> x = 10.
* case **2** -> x = 9.

![image](https://github.com/user-attachments/assets/35f109bc-0973-4574-a45c-631d69cc744f)
![image](https://github.com/user-attachments/assets/0eace066-66bf-4677-9553-c7e2cf50074a)
![image](https://github.com/user-attachments/assets/6002c29e-c890-46b9-a4e1-a37c61f3378c)

* That case not possible.

![image](https://github.com/user-attachments/assets/9a4eea66-e691-409c-97e1-396464e84eb0)
![image](https://github.com/user-attachments/assets/2aeae823-3277-496f-b01f-f73a31aca980)

* Answer -> option **3** -> 6. [1] [Answer] [Solution] [**VERY IMPORTANT**] [Practice]
* Answer -> option **2**. [2] [Answer] [Solution] [**VERY IMPORTANT**] [Practice]

![image](https://github.com/user-attachments/assets/700c9be1-c37d-4003-8a1a-717b2cbb18ce)
![image](https://github.com/user-attachments/assets/45075112-b679-4a59-95e7-940106dcbe22)

* [Question]
* 1 and 3 -> It was there that's why it came out.

![image](https://github.com/user-attachments/assets/6185ffce-5a9f-4914-98cb-b15174f1bf18)
![image](https://github.com/user-attachments/assets/c108ad22-36bb-45d7-9fb8-e430e4a653be)
![image](https://github.com/user-attachments/assets/efb602cc-8949-4a40-8598-549505b678b4)

* For every switch we are getting '2' drinks. So, in every row there should be '2' right and in every column there should be '2' right.
* In 1st row we have '3' crosses and '1' correct, so the left row 'lemon tea' should be correct as well.

![image](https://github.com/user-attachments/assets/c522121e-697d-45dd-b485-e4a1e421b830)
![image](https://github.com/user-attachments/assets/aa29e9c2-14e8-4abf-ade9-9d093a92bd95)
![image](https://github.com/user-attachments/assets/ebd14e48-e212-48d6-9194-5a8f0c2a485a)
![image](https://github.com/user-attachments/assets/89ec69a8-999c-4c09-a73b-c426c29f9e17)
![image](https://github.com/user-attachments/assets/aea38ca0-fc82-4d07-99ee-310f90174e62)

* [Answer] [Solution] [**VERY IMPORTANT**] [Practice]

![image](https://github.com/user-attachments/assets/9107d2cd-15a2-4cea-8631-ae5db343d1df)

* [Question]
* Sahil is saving doubts that the answer is in it's 30s.

![image](https://github.com/user-attachments/assets/f9ac9794-ac3f-41fd-b371-9ddc9a309401)
![image](https://github.com/user-attachments/assets/07bfd6dc-39f3-4089-a261-8ae8d6984435)

* We are asking the last statement means that we are left with '2' nos and one of them is in 30s and the other is not in 30s. 

![image](https://github.com/user-attachments/assets/d1a43d63-43d9-4fef-88cb-2a04af20f493)
![image](https://github.com/user-attachments/assets/024b474b-d7ad-4ea5-acbf-afd784dd4a07)

* Girl's response -> no, yes, yes.
* Is multiple of '4'(4k) -> girl's response of 'No' is incorrect because none of the nos. are in 30s.

![image](https://github.com/user-attachments/assets/9792babb-331f-4bb5-bc49-18f8fcaf137d)
![image](https://github.com/user-attachments/assets/e4363f03-f3e7-4943-bcd6-3d5c3ef979de)

* In **exam**, check using the **options**. [Formula] [**VERY IMPORTANT**]

![image](https://github.com/user-attachments/assets/c7de8a53-8f90-4923-8935-8a9f1169fba7)

* Answer -> option **c**. [10] [Answer] [Solution] [**VERY IMPORTANT**] [Practice]

![image](https://github.com/user-attachments/assets/242beca7-cb9d-418e-a907-89f2537b02a8)
![image](https://github.com/user-attachments/assets/b76125bd-3b9f-49c7-bd28-dfe189bc1f98)

* Greater than 50, not a multiple of '4' -> 81.
* Answer -> option **c**. [9] [Answer] [Solution] [**VERY IMPORTANT**] [Practice]

![image](https://github.com/user-attachments/assets/a9e3a3f3-2ef6-418e-bba2-93210a691efb)

* [Question]
* For any team:-
* Win(w), Loss(l), matches missed(m)
* w -> x.
* l -> y.
* m -> y.
* This is true for bhopal also because bhopal sat out the first game and lost their last game.
* For bhopal -> no. of matches lost = no. of matches missed -> l = m = y.

![image](https://github.com/user-attachments/assets/68028709-6189-40c7-ae1f-09ba0d80e0ed)
![image](https://github.com/user-attachments/assets/b4ebf9ba-b592-4496-b221-d2f6d2032d8b)
![image](https://github.com/user-attachments/assets/4ad27b2e-c7c0-4ef7-b0f6-490af5990302)
![image](https://github.com/user-attachments/assets/3557f81f-00c4-47a1-aa08-eb3d5220cbce)

*  Sum of all of the wins from all the teams -> 11.
*  Tournament has '11' matches -> '11' matches won.
* no. of matches won by each of the teams -> 1,3,7 -> 1 + 3 + 7 -> 11.
* 1 + 5 + 5 -> 11.
* 3 + 4 + 4 -> 11.
* 7  + 2 + 2 -> 11.

* Answer -> option **b** -> 7. [11] [Answer] [Solution] [**VERY IMPORTANT**] [Practice]
* Answer -> option **b** -> 2. [12] [Answer] [Solution] [**VERY IMPORTANT**] [Practice]

## Alphanumeric Puzzles(5)

![image](https://github.com/user-attachments/assets/223eb3c4-7f0e-416b-979f-e10eb8642ae8)

* [Question]

![image](https://github.com/user-attachments/assets/58eaf8cc-b0c0-4837-bbe0-7dbc18d98aeb)

* There are only '2' possibilities where it will be either '1,1,1' or '2,1,0'.
* '1,1,1' -> '3' teams have won once(1) each.
* '2,1,0' -> '1' team wins twice(2), '1' team wins once(1), '1' team wins none(0).
* Hockey score -> No. of goals.
* '1,1,1' -> This is not a option because the highest total score is done by the team who has lost the most but in '1,1,1' nobody has lost the most, everyone has won only once(1).

![image](https://github.com/user-attachments/assets/bf6b17e0-0b28-4d55-a7e3-3efcbc66e66c)
![image](https://github.com/user-attachments/assets/76d0b352-9aa7-4a4f-a90b-5232381f54a9)
![image](https://github.com/user-attachments/assets/93005c89-743b-42f4-a340-d92698b505b9)
![image](https://github.com/user-attachments/assets/a4ab3668-647a-41e9-a30b-60fd50171cd1)

* Answer -> option **b** -> 2. [2] [Answer] [Solution] [**VERY IMPORTANT**] [Practice]
* Answer -> option **c**. [1] [Answer] [Solution] [**VERY IMPORTANT**] [Practice]

![image](https://github.com/user-attachments/assets/bad7675a-9e67-4111-a728-0f804b7a7d23)
![image](https://github.com/user-attachments/assets/0f2ed676-1a31-4032-8b99-c485fd8706fa)
![image](https://github.com/user-attachments/assets/b43dc84d-8912-4c7f-8bc8-1bdc952d7a4b)

* [Question]

![image](https://github.com/user-attachments/assets/597ead5c-6850-4eb3-a849-b2a80c88944c)
![image](https://github.com/user-attachments/assets/a15582a6-6b0d-4e92-8bf1-acd3b8e88642)

* We can swap between 'A and S' who will be carrying back the torch and get the same time.
* Answer -> option **2** -> 20mins. [3] [Answer] [Solution] [**VERY IMPORTANT**] [Practice]
* Answer -> option **3**. [4] [Answer] [Solution] [**VERY IMPORTANT**] [Practice]
* Answer -> option **2** -> 2. [5] [Answer] [Solution] [**VERY IMPORTANT**] [Practice]

![image](https://github.com/user-attachments/assets/d69e3f6e-eb58-4f3b-bcc0-add7d4ec986a)

* Same above question but with '5' people. [Question]

![image](https://github.com/user-attachments/assets/c296f278-32d2-4a08-97f6-e6e6985997f5)
![image](https://github.com/user-attachments/assets/86ed3728-88cf-495b-8e5d-c3bfbd942da0)

* Answer -> 30mins. [Answer] [Solution] [**VERY IMPORTANT**] [Practice]

![image](https://github.com/user-attachments/assets/317c11b9-ac45-4760-9f1d-65ce0a9cd012)

* '6' people.

![image](https://github.com/user-attachments/assets/8ad216ff-25d3-4970-b4e4-0ebe6003f836)
![image](https://github.com/user-attachments/assets/b976df0a-d187-4111-8c74-9249599b296d)

* '4' combinations.

![image](https://github.com/user-attachments/assets/955cff43-4f2f-48ae-aead-f2f12c831cb8)

* [Question]

![image](https://github.com/user-attachments/assets/547c79a9-a9b9-4c10-8aff-bb42d4f42170)

* We have to minimize the total.

![image](https://github.com/user-attachments/assets/973559f4-0fdc-4ef0-9645-30afdf35606f)
![image](https://github.com/user-attachments/assets/153a30e1-caf4-4802-a2ba-7dd1c56b5ba5)
![image](https://github.com/user-attachments/assets/76cf18b2-9492-4530-be13-80000ee359ac)

* Total -> a + b + c -> union/sum. [Formula] [**VERY IMPORTANT**]
* Exactly one(1) -> a -> counted once(1). [Formula] [**VERY IMPORTANT**]
* Exactly two(2) -> b -> counted twice(2). [Formula] [**VERY IMPORTANT**]
* Exactly three(3) -> c -> counted thrice(3). [Formula] [**VERY IMPORTANT**]

![image](https://github.com/user-attachments/assets/5cc5bb73-2d9d-4980-8b08-319c46c32c8f)

* c = 0.
* We have to make minimum -> a + b + c. 
* We have to make minimum -> a + b. [c = 0] 

![image](https://github.com/user-attachments/assets/7fbcab68-eebb-4d40-a057-0a05cdc69881)
![image](https://github.com/user-attachments/assets/4474a831-ea90-4db2-bac4-a573c125b87e)
![image](https://github.com/user-attachments/assets/2cbe1c55-41a7-49da-bda6-574bb7a4484c)
![image](https://github.com/user-attachments/assets/5f521f54-a15f-4254-9110-6bde223cb6ec)

* a = 1, b = 167.
* 1 + 167 -> 168.

![image](https://github.com/user-attachments/assets/f7b8d222-54e7-4e44-a3bb-a58aea6b1316)

* a = 1, b = 212.
* 1 + 212 -> 213.

![image](https://github.com/user-attachments/assets/a51db5cc-fcb8-4f9d-a9d4-d014837f5993)

* a = 1, b = 137.
* 1 + 137 -> 138.

![image](https://github.com/user-attachments/assets/b1a8eb65-645b-423d-ae83-493ddd911959)

* a = 1, b = 82.
* 1 + 82 -> 83.

![image](https://github.com/user-attachments/assets/60289899-15d7-4ac1-9318-9840a9ff0d7e)

* Total -> 168 + 213 + 138 + 83 -> 602.
* These are the min. values in each group -> 168 + 213 + 138 + 83 
* Should be take '602 or 600'?

> We taking '602'.

![image](https://github.com/user-attachments/assets/c50a589b-f733-4b38-8c21-188760c8a7e5)

* If the addition total was '598' then we would have taken the '600' as the **answer**. [Concept] [Logic]

![image](https://github.com/user-attachments/assets/9cca4ab6-bcf2-45bf-b940-23c8f12c9708)

* U -> Union.
* Acting U Dancing -> 160 U 75 -> worst case scenario -> 75 -> can't be more than '75'.
* 120 U 105 -> worst case scenario -> 105 -> can't be more than '105'.
* 60 U 90 -> worst case scenario -> 60 -> can't be more than '60'.
* 60 U 30 -> worst case scenario -> 30 -> can't be more than '30'.
* 75 + 105 + 60 + 30 -> 270.

![image](https://github.com/user-attachments/assets/46649459-af55-4cee-9f78-be24fc8c1416)

* 160 - 75 -> 85.
* 85/160 * 100 -> 53.125%

![image](https://github.com/user-attachments/assets/8a197ea6-d51e-430f-9fae-a56c2420054f)

* Option **D** -> CBD.

![image](https://github.com/user-attachments/assets/560ccf5f-d578-434a-b4ac-5dcd7c4a4d5a)
![image](https://github.com/user-attachments/assets/698da44a-9a6e-4622-bc30-4e0f1bda7d90)
![image](https://github.com/user-attachments/assets/0ea8b2d8-d262-442e-bd8f-ea2e466a805f)

* [Question]
* For next class.

## Venn Diagram (6) 

![image](https://github.com/user-attachments/assets/d4fec646-7d48-43c7-83f0-62df4124b7a2)
![image](https://github.com/user-attachments/assets/1b6c0e35-4635-44c5-aa47-59b787a57d83)

* [Question]
* '6' people and they travelled for different time. We have '6' times.
* '6' people -> '6' times -> 10,20,30,40,50,60.

![image](https://github.com/user-attachments/assets/a32ebd89-72a2-4950-aa59-af811d6d3f47)

* Person got on station '1' and left on station '7' -> Time is '60mins'.
* Max. is '60mins'.
* Least amt. of time -> 10mins.

![image](https://github.com/user-attachments/assets/3c73f91c-7acf-4f39-b4b6-c56c838e0c43)

* P's max -> 40.

![image](https://github.com/user-attachments/assets/54d5fa31-2767-469a-ad61-142995cc4fca)

* 'V' boarded before 'S'.

![image](https://github.com/user-attachments/assets/0e9bee24-2e17-4eed-8f9b-43cbd00e8423)
![image](https://github.com/user-attachments/assets/30aa1a38-146c-481e-8856-881505e836a2)

* We have '2'combinations.
* If some is there for a duration of '60mis' then they boarded on station '1' and left at station '7'.
* 'S' cannot do '60mins' because when 'S' boarded, 'V' was already on the train. 'S' boarded after 'V'.
* 'V' -> 60mins.
* 'S' -> 50mins. 

![image](https://github.com/user-attachments/assets/0962ffb9-ebcf-4b4f-b575-12afcbed2716)
![image](https://github.com/user-attachments/assets/153831a9-a7ee-40e6-8da9-7963e1a60ac0)

* '50mins' has '2' possibilities which are from '1 to 6' or from '2 to 7'.

![image](https://github.com/user-attachments/assets/7b42a028-ebdd-45a4-b86c-970b1086fb60)

* T_k + T_A -> 50mins.

![image](https://github.com/user-attachments/assets/3cfd9739-8521-43df-8e4c-f5cf21e6f04a)

* 'k' departed/left before 'p'. 'p' departed/left at '6', so 'k' has to departed/left before '6'.

![image](https://github.com/user-attachments/assets/819a7fdd-6a15-4005-be9d-40a36d4aff59)
![image](https://github.com/user-attachments/assets/37d16649-22ad-4990-9a26-abbb623e3fc3)

* 'k' boarded at '1' and 'A' departed/left at '6'.

![image](https://github.com/user-attachments/assets/8a470da1-dc14-479b-9f0d-97fc9c68b699)
![image](https://github.com/user-attachments/assets/65ac4c95-1b04-4350-b413-4f6c0e552a9c)

* Case **1** correct.

![image](https://github.com/user-attachments/assets/7d9f0b9c-533b-4bfd-847e-3ab49b7536d3)
![image](https://github.com/user-attachments/assets/b91fa0ee-07d3-4615-87ee-78616ca46e84)
[image](https://github.com/user-attachments/assets/2127eadb-446c-474d-af1b-db1598bd70ce)
![image](https://github.com/user-attachments/assets/3590a12a-a980-49a3-aecb-50c97c423a86)

* '5' people at once is not possible.
* So 'G' can be either in '1 to 2' or from '6 to 7'.
* 'G' cannot depart at station '7' so '6 to 7' is **not possible**.

![image](https://github.com/user-attachments/assets/f7f57656-997f-4918-84ed-7512a42d6e16)
![image](https://github.com/user-attachments/assets/a74dfb63-50aa-48d7-b25e-cf3e6e0d7667)

* '2' people each departed at station '6 and 7'.
* Answer -> 2. [1]
* Hebbal -> station '2' -> '2' boarded.
* Electric City(EC) -> station '6' -> '2' departed.
* Diff -> 2 - 2 -> 0.
* Answer -> 0. [4]
* With 'A', 'V and S' were also there.

![image](https://github.com/user-attachments/assets/21506490-0572-4a44-8bd8-a8f9166a9762)

* Answer -> 'V and S' -> option **D**. [5]

### Venn Diagram

![image](https://github.com/user-attachments/assets/fc101ef6-52d4-4e9c-b568-ad797f5b3ed2)

* IV -> Intersection of all of the '4' parts.
* III -> Intersection of all of the '3' parts.
* II -> Intersection of all of the '2' parts.

![image](https://github.com/user-attachments/assets/a4908ed5-6233-483c-9baa-4033f8fe148a)
![image](https://github.com/user-attachments/assets/6aced17a-eba2-4477-95b4-577b02439053)
![image](https://github.com/user-attachments/assets/f4f0c795-7788-49a4-804a-763377ee510f)
![image](https://github.com/user-attachments/assets/0c2d9413-4c49-4277-ac57-ddd73335d598)

* Sum(S) -> I + II + III +IV.

![image](https://github.com/user-attachments/assets/b95cfbdc-62da-4bdd-ba84-74a8d36dac74)

* Overlap(x) -> 100 + 150 + 200 + 250 -> 700.

![image](https://github.com/user-attachments/assets/dceb7155-97b6-4f70-a087-e1bd16ff49ac)

* [Fomula] [Summary]

![image](https://github.com/user-attachments/assets/3e4bba14-1b23-4ca8-9634-e6ad1c621202)

* 4

![image](https://github.com/user-attachments/assets/26e03a2e-4e3e-454b-8c12-ee2350afc3dd)
![image](https://github.com/user-attachments/assets/e11b13aa-ab81-46f1-819d-420e9ffc7798)

* 3

![image](https://github.com/user-attachments/assets/ef45b7a5-43f0-4a58-90b9-e07c0ac59a44)
![image](https://github.com/user-attachments/assets/660e0696-1bcf-4773-84c0-103d6571692f)

* X -> 100 + 300 + 500 -> 900.
* The sum of the whole thing -> X. [Fomula]

![image](https://github.com/user-attachments/assets/b9734efb-e053-49ba-a1f4-afa0228d8146)

* Substraction. [Fomula]

![image](https://github.com/user-attachments/assets/c62ecf4a-530e-422c-ae13-9afa61ef7ede)
![image](https://github.com/user-attachments/assets/900e6f91-dc38-4af3-996a-33bb90f72a5e)

* [Question]

![image](https://github.com/user-attachments/assets/53fd3b7e-c69d-4ffc-9593-b23bd3637ebb)
![image](https://github.com/user-attachments/assets/7632ad14-bdd2-4b45-9229-df2beb1768e9)

* q + r + t + u -> 155.

![image](https://github.com/user-attachments/assets/022b04d4-88fe-4ef1-a2ec-5688804b8edf)
![image](https://github.com/user-attachments/assets/2b2ff436-8134-464a-9eca-91631eaf239c)

* TP but not badshah -> w + x + y + r -> 145.
* TP and badshah -> t + u + v + z.
* v + z -> 55.

![image](https://github.com/user-attachments/assets/d0c9b082-e467-438c-8330-cccee30c312f)

* TP and badshah but not PT  -> v + z.

![image](https://github.com/user-attachments/assets/3038571e-7d97-4799-9007-361a36e68c92)
![image](https://github.com/user-attachments/assets/3ea82a22-7457-4683-81cc-a573e96d9dfe)

* PT and FA -> p + r + u + x. 
* Only PT and FA -> p -> 20.

![image](https://github.com/user-attachments/assets/dc9302da-af3d-4497-b676-74db671129ba)
![image](https://github.com/user-attachments/assets/496ca3ba-644b-4b98-a4fa-0c9502a85cde)

* We need to frame **equations**.
* Badshah -> 155 + 55 + 45 + s = 300 -> s = 300 - 255.
* s = 45.

![image](https://github.com/user-attachments/assets/50ee5e0e-5990-4116-9e75-c1531f92eab9)

* I = 155.
* 80 + p + 45 + r = 155 -> p + r = 30. 

![image](https://github.com/user-attachments/assets/4bf72998-dbf9-4f43-b475-e925069befc5)
![image](https://github.com/user-attachments/assets/9c81def7-e1ef-41b2-8e5d-4988a70f4cec)

* Sum(S) -> I + II + III + IV -> 575.

![image](https://github.com/user-attachments/assets/731dcc27-d8a8-4aac-b8e7-d284cf63b4b8)
![image](https://github.com/user-attachments/assets/a3d68f89-ba33-45bf-a611-c82710548329)
![image](https://github.com/user-attachments/assets/ab05af93-78d3-408c-9f35-6fec96f44ace)

* IV -> III - 68 -> 143 - 68 -> 75.
* IV = 75.
* III = 143.
* III -> r + t + x + v = 143.

![image](https://github.com/user-attachments/assets/d547737a-be94-4d9a-a67a-3679fa56647e)

* We don't know 'v and y'.

![image](https://github.com/user-attachments/assets/f340714a-52bf-4b29-ba9f-d1b384c7c1c4)
![image](https://github.com/user-attachments/assets/6ca2a483-af56-491f-8058-e38a05d548a7)

* Only 'P' is left.
* Total sum -> 80 + 20 + 155 + 45 + 55 + 45 + 145 -> 545.
* Original total -> 575.
* P = 575 - 545 = 30.

![image](https://github.com/user-attachments/assets/da97b7fb-efb1-43f8-be07-c68174c5e823)

* P + r = 30.
* r = 0.

![image](https://github.com/user-attachments/assets/b67b5f56-69da-4fb2-9901-c761b61cbee6)

* Answer -> 0 [1]
* Answer -> 30 [3]
* Only (TP + bad + PT) -> u -> 75. [2]
* Only (TP + FA + PT) -> III -> x. 
* Only (TP + PT) -> w.
* Only (TP + bad + FA) -> III -> v. 

![image](https://github.com/user-attachments/assets/5b62e8cb-5cf4-45c0-a71f-eba78c29a7d9)
![image](https://github.com/user-attachments/assets/646b75f3-181b-451e-8b52-d572ed516a41)

* v + z = 55. [We know]
* r + t + x + v = 143 -> 0 + 75 + x + v = 143 -> x + v = 68.
* w + x = 95.

![image](https://github.com/user-attachments/assets/a5a33f6d-a93a-4d28-a6bd-976aa1165e62)
![image](https://github.com/user-attachments/assets/0e451e3b-2450-4611-8ecb-49fe01cc7685)
![image](https://github.com/user-attachments/assets/0eb679e3-5764-4aee-9a87-57f54fc95b4b)

* x = 40.
* 95 - x -> 95 - 40 -> 55.
* w = 55.
* v = 28.

![image](https://github.com/user-attachments/assets/fe16ca08-d7c9-49bf-a686-dd8de1acc33e)
![image](https://github.com/user-attachments/assets/566bfaa7-33ca-4cb8-85cb-e576b989be68)

## Mixed Practice (7)

![image](https://github.com/user-attachments/assets/62de488d-1a3d-47ae-a4f5-5547949b6b92)
![image](https://github.com/user-attachments/assets/2b2412c9-f06a-4a6a-b793-12d6eea23ee7)
![image](https://github.com/user-attachments/assets/348bbba1-937f-485c-a205-b28a9f568044)
![image](https://github.com/user-attachments/assets/434f3f5d-c8d1-42cc-b38a-f8200184cb34)

* [Question]
* 4-parameter venn diagram.
* Atleast '3' dishes -> III + IV -> 50.
* Atleast '2' dishes -> II + III + IV -> 182.
* Atleast '1' dishes -> I + II + III + IV -> 295.
* Both CB and MB -> B,L,P,H -> 0.
* Both CB and DF -> K + L + J + P -> K + J. [J = 0, P = 0] 
* Both MB and DF -> L + M + P + N -> M + N. [L = 0, P = 0] 

![image](https://github.com/user-attachments/assets/fe1c3d80-f61d-43af-92a8-0bb0573f4647)

* 'PK' is not ordered without 'DF'.
* 'PK' without DF -> all of them -> '0'.

![image](https://github.com/user-attachments/assets/b11ef523-f5e4-4005-8088-bdf6cf58ddf8)
![image](https://github.com/user-attachments/assets/71e3cd3b-03e8-496b-b0cf-0359ba0af697)

* IV = 0.
* III = 50.
* L + J + H + N -> III -> 50. [L = 0, H = 0]
* J + N = 50. 

![image](https://github.com/user-attachments/assets/e4e1ff15-2c23-453d-9b53-2e21c6d922bb)

* II + III -> 182. [III = 50]
* II = 132.
* B + K + M + I + G + E -> II = 132.
* K + M + E = 132. 

![image](https://github.com/user-attachments/assets/979dc532-240d-45a9-8359-e76c2091d370)
![image](https://github.com/user-attachments/assets/c5a09fe4-acdc-40b6-94b2-edfb3d8bf9e0)
![image](https://github.com/user-attachments/assets/88c005a7-dca2-4050-ad96-64b270da292d)

* I = 113.
* A + C + D = 113.
* C + M + N -> Total no. of people who ordered MB.

![image](https://github.com/user-attachments/assets/ac386afd-ca5a-4122-9868-c7f61c1b2dbd)

* Weighted Average. [**IMPORTANT**] [Formula] [Concept]
* C * 1 -> 'C' people ordered '1' dish.
* M * 2 -> 'M' people ordered '2' dishs.
* N * 3 -> 'N' people ordered '3' dishs.
* C * 1 + M * 2 + N * 3 -> Total no. of MB dish ordered.

![image](https://github.com/user-attachments/assets/29a079fc-c0e3-48e7-b03d-9c0e25b37e97)
![image](https://github.com/user-attachments/assets/841de6c8-8375-4970-82df-f4afed424b8f)

* We have do **cross-multiplication**.

![image](https://github.com/user-attachments/assets/b03c62f6-8f2a-4e9c-bad0-2059bae6737d)
![image](https://github.com/user-attachments/assets/3cb4d9f8-4c89-427c-9f92-79d6e8d8c419)
![image](https://github.com/user-attachments/assets/15c42054-fe8f-480a-9af1-63f10b82adac)
![image](https://github.com/user-attachments/assets/79230faa-7159-4b4a-8ce7-11fa09a1f6a8)
![image](https://github.com/user-attachments/assets/cf62b5e3-30e4-447f-89a5-e41a21e31a10)

* D = E.
* J + N = 50.
* D = E = 50.

![image](https://github.com/user-attachments/assets/43beb7b6-feb9-4694-802d-36a5fa83009c)
![image](https://github.com/user-attachments/assets/3e1b4587-52dc-49fc-9402-a957d477cdd6)
![image](https://github.com/user-attachments/assets/47de6cc8-aae8-49c6-a60d-485e1dcbcc71)
![image](https://github.com/user-attachments/assets/4625ad0c-3063-4467-9a36-503c19cdf24e)

* Total Venn Diagram -> 295.
* Left -> 295 - D - E -> 295 - 50 - 50 -> 195.
* A + C + K + M + J + N -> 195.

![image](https://github.com/user-attachments/assets/6c0fc698-cd9e-4388-ae07-de11d62b2869)

* A + C -> 63.
* K + J -> 48 + M + N.

![image](https://github.com/user-attachments/assets/0a6af71d-fa94-4017-a5a2-0c72aac7efa1)
![image](https://github.com/user-attachments/assets/171a3921-4fb7-404b-8c0f-bef3087a9bf2)

* C = N + 13.

![image](https://github.com/user-attachments/assets/c59cf0fc-1151-467f-b058-54c0fa662303)
![image](https://github.com/user-attachments/assets/4e6de099-1bc8-4bfc-9a91-a8176176e950)
![image](https://github.com/user-attachments/assets/8f5a68c4-bb5b-4fff-abc4-399665255f14)

* N = 10
* C = N + 13
* C = 23.
* A + C = 63.
* A = 40.
* J = 40.
* K + A = 90
* K = 50.

![image](https://github.com/user-attachments/assets/de4e124f-5295-43a1-8448-0b2ed8cd2242)
![image](https://github.com/user-attachments/assets/2bd9ab14-5c85-44d9-9956-2ef6526ddc8d)
![image](https://github.com/user-attachments/assets/e769bad3-f328-4675-9caf-085dae7ebdd8)
![image](https://github.com/user-attachments/assets/2c2c39b4-6c9a-4e9c-bf40-f5f3e1a2ec7e)

* [Question]
* max. -> be careful. [**IMPORTANT**] [Logic] [Concept]
* Total -> 100 people. [Let]
* Max. -> 10%.
* 1/3 of 100 -> 66.67
* We have to take '4' steps so that we can reach '1/3' faster. We cannot do so in less than '4' days.

![image](https://github.com/user-attachments/assets/5aa8c46d-6aaf-413d-84c3-662fab081a89)
![image](https://github.com/user-attachments/assets/fe4dfdcb-7920-473c-aadb-4ce70e47fc8d)

* Max. we can keep same is  'F, S, Su, M'.
* According to the question, the '1/3' reduction is applicable to the mondays of the month of april only. [Logic] [**IMPORTANT**] [Concept]

![image](https://github.com/user-attachments/assets/1c4cdaac-38ba-42ae-b7da-0a49cdebf253)
![image](https://github.com/user-attachments/assets/e6e748f5-9ff5-4691-b0a4-83bacd987a7a)
![image](https://github.com/user-attachments/assets/ef6540e9-90cd-4eba-ac46-ccfbe159b3de)

* 25th April -> Last Monday of april
* 2nd May -> Next Monday.
* We are in may now and the '1/3' reduction worked in april only.
* 4th Apr to 11th Apr -> 4days.
* 11th Apr to 18th Apr -> 4days.
* 22th Apr to 30th Apr -> 9days. [1] [Answer] [**VERY IMPORTANT**]
* 9 > 4. 

![image](https://github.com/user-attachments/assets/96637037-8c6f-46d8-80f3-82d8f29e185f)
![image](https://github.com/user-attachments/assets/a23b5c8f-1fbf-4e07-be44-aee4638cc6d1)

* We have to maximize on '1st of april' because after that everytime the no. of workers are getting reduced. [Logic] [**IMPORTANT**] [Concept]

![image](https://github.com/user-attachments/assets/ce031eab-e69a-47da-b135-3de9ec90108d)
![image](https://github.com/user-attachments/assets/2e6546ee-de61-47f7-8bc8-aee7362cb7a9)

* [Formula] [**IMPORTANT**] [Concept]

![image](https://github.com/user-attachments/assets/e8a22628-44ef-48fe-819d-5cf7c14b329d)
![image](https://github.com/user-attachments/assets/50d3f7c8-fceb-4344-9f40-7e83d1ae7b19)

* 55 to 49 -> 11% decrease.
* Max. is 10%. So we cannot take '55', we will take '54'.

![image](https://github.com/user-attachments/assets/7b23e66c-2afc-4665-a40d-09c80d98fdb3)

* Jump from 11th april to 4th april.
* 10% decrease -> 1/10 = n/n+d -> n = 1, d=9.
* n/d = 1/9 increase.
* We we go from 1st to 2nd april -> 10% decrease.
* We we go from 2nd to 1st april -> 1/9 increase.

![image](https://github.com/user-attachments/assets/96309c92-886a-4b41-9fe0-6135d3b77547)
![image](https://github.com/user-attachments/assets/2548b1e5-8657-45cb-aa68-89511b180012)

* Max -> 111. [Answer] [2] [**VERY IMPORTANT**] 

![image](https://github.com/user-attachments/assets/1db28fb0-a90b-4aa5-a15b-ebd8ab27ac54)
![image](https://github.com/user-attachments/assets/24587626-8c4b-41e5-b780-3d6a6c8dbe72)

* We have to maximize.
* The women work force is **increasing** as the months goes on. So we can maximize on 30th april.
* It is opposite to men as men work force is **decreasing** as the months goes on. So we can maximize men on 1st of april.
* Max. increase is '10%'.
* 4th april -> x. [Let]
* 11th april -> 1.5x -> 26.
* 'x' will not be an **integer**. So it cannot be '26'. We know that it has to be greater than '19' but less than '26' and we can find the '50%' of that number.
* Only possible no. is '24'. It has to be '24'.

![image](https://github.com/user-attachments/assets/3a2db3bb-91c5-461e-a131-97c71d7ff8b2)
![image](https://github.com/user-attachments/assets/41e8fd93-af8f-4793-93b3-2701e96fdf8d)
![image](https://github.com/user-attachments/assets/3ff20004-e53d-4f4c-9072-a7d781f9ff82)
![image](https://github.com/user-attachments/assets/0d155dc4-58a7-4d2a-9a8c-1fa20c71d0b3)

* We have to keep it less than '10%'. Max. is '10%'.
* Max -> 84. [3] [Answer] [**VERY IMPORTANT**] 

![image](https://github.com/user-attachments/assets/4bc615a3-724f-4ce4-8fbe-81a668d3d073)

## Venn Diagram Practice

![image](https://github.com/user-attachments/assets/78a8a88d-7009-49ab-bb5c-dbd477d84201)
![image](https://github.com/user-attachments/assets/c6636136-1702-462c-9868-f0a1daf13535)

* [Question]
* Member of 'R' -> e + g + f + c.
* Not member of 'R' -> a + d + b.
* Member of '1' group -> a + b + c.

![image](https://github.com/user-attachments/assets/0c75c2ba-4cd1-48cd-9804-613d36b23359)
![image](https://github.com/user-attachments/assets/db834acf-b1af-4a37-8019-209dab8b34d3)

* Members of atleast '2' groups -> d + e + f + g.
* Total -> 25.

![image](https://github.com/user-attachments/assets/76d551f6-247f-4de6-870f-5898de6aca7e)
![image](https://github.com/user-attachments/assets/63f85f35-9fcd-43d3-b547-5ac94a732a0c)

* Only case possible is 'g = 5' and 'd + e + f' can be either '3 or 4'.

![image](https://github.com/user-attachments/assets/71f6753a-942f-4b35-87e1-b0514f09c039)
![image](https://github.com/user-attachments/assets/10548fd0-bdc7-4278-8b32-9339dce56952)
![image](https://github.com/user-attachments/assets/5e13f24a-0946-48ce-9480-87ca6c92ff49)
![image](https://github.com/user-attachments/assets/b7e1098b-6d19-4769-9ce3-1d5883861725)

* '1' case is only possible.
* d + e + f = 3.
* a + b + c = 17.

![image](https://github.com/user-attachments/assets/7974e17f-d15d-4951-8d38-a71541acc8ef)
![image](https://github.com/user-attachments/assets/364c76d5-b015-4514-8f06-b6acf68195bb)

* Answer -> g = 5. [1] [Solution]
* R = e + c + f + g [g = 5]

![image](https://github.com/user-attachments/assets/109cac25-96f3-4b96-b02f-10fa4d7d1415)

* Sum should be '20'. 

![image](https://github.com/user-attachments/assets/070acc14-33db-430e-8fea-9c8d1f025b53)

* R > 14.
* All of the options for question **2** are greater than '14'. So it is **CBD**.
* Answer -> option **D** -> CBD. [1] [Solution]

![image](https://github.com/user-attachments/assets/f52946c7-b59b-4547-aeb1-bbaca97e648a)

* Question **3 and 4** have some extra info for them.
* Between '2' groups 'P and R' -> e + g. 
* Between '2' groups 'Q and R' -> f + g. 

![image](https://github.com/user-attachments/assets/207234f2-de29-47a7-a20f-a5abfa6ca4b3)

* e = f = 1.
* Exactly '2' groups -> d + e + f.
* 'P' group alone -> a.
* d + e + f = 3.
* * d + e + f = a = 3.
* 'R' group alone -> c. [Find]
* 'Q' group alone -> b. [Find]
* Sum = b + c.
* a + b + c = 17. [a = 3]
* b + c = 17 - 3 = 14.
* b + c = 14. [3] [Answer]

![image](https://github.com/user-attachments/assets/5fa2a338-1ed4-4fc4-8fa6-0ccb8cbfe19b)

* Members of 'P' = a + e + g + d.
* d + e + f = 3. [e = 1, f = 1]
* d = 1.

![image](https://github.com/user-attachments/assets/10ef3647-bb70-4aa3-aefb-b6eb3bd3b864)
![image](https://github.com/user-attachments/assets/505ca3e3-8abe-4739-b9d7-ac103a30d630)

* 'P' = a + e + g + d -> 3 + 1 + 5 + 1 -> 10. [4] [Answer]

![image](https://github.com/user-attachments/assets/5b0e38e7-912a-43dd-87f7-103ab49a04a1)
![image](https://github.com/user-attachments/assets/a5469ca4-c770-4e58-a305-30449fe136c2)
![image](https://github.com/user-attachments/assets/3611b4b4-ac66-4ce0-88b6-b7412cf3681e)

* [Question]
* Total -> a + b + c + d + e + f + g + h = 100.
* Exactly '1' movie -> a + b + c
* IAK -> e + g + b + f.
* IAK and ETT -> g + f.
* AT and ETT but not IAK -> d. 

![image](https://github.com/user-attachments/assets/79738f82-908e-4dda-a927-c6a2507a71e1)

 * AT and IAK -> e + g.
 * None of the students in the category of 'e + g' who haven't watched 'ETT'. Everyone has watched 'ETT'. It means that 'e = 0'.

![image](https://github.com/user-attachments/assets/ff8d9afc-b009-4b19-8ed9-29e4bece0a73)
![image](https://github.com/user-attachments/assets/bb38eb11-cd3f-4750-92dd-201d81ed3fe6)

* Haven't watched any of the '3' movies -> h.
* Atleast '1' of the '3' movies -> S -> a + b + c + d + e + f + g.

![image](https://github.com/user-attachments/assets/2fbf25e8-4727-420e-b262-c8324950578f)
![image](https://github.com/user-attachments/assets/60c141df-79bf-4222-9362-fc0c562ea6a8)

* Exactly '2' movies -> d + e + f.
* All '3' movies -> g.
* d + e + f = 16 + g [e = 0]
* d + f = 16 + g.

![image](https://github.com/user-attachments/assets/e5a93ee4-c3f9-4e35-b693-5a8a4f89f129)

* We have to minimize the no. of variables.

![image](https://github.com/user-attachments/assets/42e97917-e426-48e3-ae5b-cdf8d95fb15b)
![image](https://github.com/user-attachments/assets/c3ddf1b4-dae5-414e-9623-5395a58a6dfa)
![image](https://github.com/user-attachments/assets/da33726f-10ce-4e5e-8424-164b7a8ad717)
![image](https://github.com/user-attachments/assets/5f665300-768a-433a-be2f-a524bc6dabb1)

* g = d + 2.
* Convert all in 'd'.
* 'b' is already cancelled. We cannot convert it into 'd'.

![image](https://github.com/user-attachments/assets/8fbcf29f-6b71-47d4-9b64-a2152c17a95f)
![image](https://github.com/user-attachments/assets/bea6e4fc-6f44-4d08-9edb-a9503c3dd124)

* Definite set.
* More than '1' movie -> 0 + d + (d + 2) + 18.
* We need to maximize '2d + 20'.
* (2 * (d + 20))/3 + (d + 20)/3 -> 2x/3 + x/3 -> 3x/3 -> x -> d + 20.

![image](https://github.com/user-attachments/assets/7ff12485-1031-4a58-9674-bc67c2e00aa1)

* We have to maximize 'd'.
* To maximize 'd', we have to minimize 'b'.

![image](https://github.com/user-attachments/assets/99bb705b-1c8e-45e3-9dd7-754cb1874a16)
![image](https://github.com/user-attachments/assets/c204d1a4-435b-48a1-9511-c8e3b3a02baf)

* 'h' min is '1'.
* 'k' max is '99'.
* 59/3 -> Not an integer.
* Integer will come when 'b >= 2'.

![image](https://github.com/user-attachments/assets/0d725af6-0c95-411c-bbb7-e4517b7d8ef0)
![image](https://github.com/user-attachments/assets/7707ddfe-d46f-4782-b86f-fa631d819ba6)

* Even if 'b = 0' then 'd' max is '19'. With 'b = 2' we are getting 'd' max as '19'.
* 'd' max as '19'
* Max. students who watched more than '1' movie -> d + 0 + 18 + d + 2 -> 2d + 20. 

![image](https://github.com/user-attachments/assets/aa8dd727-e1cb-4130-9241-492eda96a5a3)
![image](https://github.com/user-attachments/assets/142b0c2b-163a-436b-907d-e7a4e3882ae0)
![image](https://github.com/user-attachments/assets/d86ac755-6609-42dc-9ccd-a51ba960e921)

* Answer -> 58. [1] [Solution]

![image](https://github.com/user-attachments/assets/12b4cbb0-c4e0-4149-ae30-ce147579c2fa)
![image](https://github.com/user-attachments/assets/83644bdf-705b-43c0-9aaf-f94f3967590b)

* Only IAK -> max. value of 'b'.
* To maximize 'b' we need to minimize 'd'.
* '(d + 20)/3' should be an **integer**.
* 'd' min is '1'.
* 'h' min is '1'.
* 'k' max is '99'.
* Answer -> 56. [2] [Solution]

![image](https://github.com/user-attachments/assets/c8636d70-a31c-4988-929d-9358c12ae582)

* Exactly '2' movies -> d + 0 + 18 -> d + 18.
* None of the '3' movies -> h.
* d + 18 = h.
* Exactly '1' movies -> a + b + c -> Find?
* 'd' cannot be '0' because we want '(d + 20)/3' to be an integer. So 'd = 1'.
* 1 <=h<20 -> 'h' is less than '20'.
* So 'd = 2' is not possile as we will get 'h = 20'.

![image](https://github.com/user-attachments/assets/a173fa7f-c467-49f9-a8fe-c3142aaea811)

* Only possibility.
* h = 19.
* Total -> 100.
* Inside venn diagram sum -> 100 - 19 -> 81.

![image](https://github.com/user-attachments/assets/24d356c3-b0e2-47df-9603-0173c94bf59d)

* We want the value of 'a + b + c'.
* a + b + c -> (2 * (d + 20))/3 + b + (d + 20)/3 -> d + 20 + b.

![image](https://github.com/user-attachments/assets/6521536f-bc88-494c-9367-fb5f54d18829)
![image](https://github.com/user-attachments/assets/3c622f69-41f4-4570-ac6f-5eb9866b1eb4)

* a + b + c -> d + 20 + b -> 1 + 20 + 38 -> 59. [3] [Solution]

![image](https://github.com/user-attachments/assets/b23f4169-9201-4bd2-9ed6-8769304ab143)

* IAK =  ETT -> b = (d + 20)/3.
* All movies watched -> g -> d + 2.
* None movies watched -> h.

![image](https://github.com/user-attachments/assets/7b2a912c-c2c8-4df9-88bc-4366accd8050)
![image](https://github.com/user-attachments/assets/b7fbdef7-ed54-41fb-b637-51dcd8e28956)

* 'd' should be an integer.
* For 'd = 13' in '(d + 20)/3' we are getting 'd' as an integer.
* d + 20/3 -> 13 + 20/3 -> 33/3 -> 11 -> integer.

![image](https://github.com/user-attachments/assets/7f7f6119-d4ef-4f71-8643-c356c5b15009)
![image](https://github.com/user-attachments/assets/558d56da-7428-472c-b0b1-3b2351ffcf34)

* Venn diagram value(Vd) inside -> Atleast '1' movie case -> 3d + 40 + b.
* b = d + 20/3 [d = 13]
* b = 33/3 = 11.
* 3d + 40 + b -> 90.
* h = 100 - 90 -> 10.

![image](https://github.com/user-attachments/assets/68608940-36fe-4e2c-a787-760970f01f4b)

* Answer -> 150%. [4] [Solution]

![image](https://github.com/user-attachments/assets/3692454f-77a3-492b-a7d0-b0a20f86a14a)
![image](https://github.com/user-attachments/assets/d8bbcf0e-d5b1-420f-8b78-8c54f675c6f5)
![image](https://github.com/user-attachments/assets/286049d3-6a1b-4102-b273-7a0f833d5a5c)
![image](https://github.com/user-attachments/assets/591a3a19-7bc2-40aa-9607-c6e65bd412cd)

* '2' products were not sold.
* [Question]

![image](https://github.com/user-attachments/assets/a59dc2cb-56a7-4fd0-9468-efced70b14c0)
![image](https://github.com/user-attachments/assets/c03ab327-9d4e-478e-bf4e-ee9bb0438feb)

* '2' products were not sold.
* '3' product type.
* Exactly '1' box -> a + b + c.
* Exactly '2' box -> e + d + f.
* Exactly '3' box -> g

![image](https://github.com/user-attachments/assets/8168bec8-bdeb-4fa0-bca7-bef326d9bfb6)
![image](https://github.com/user-attachments/assets/9a0bef1d-f770-4a38-92c4-92a1f4ad4c1d)
![image](https://github.com/user-attachments/assets/6b238ede-e8cf-4b10-b3a4-48ec0229fa6d)

* Problem with question.

![image](https://github.com/user-attachments/assets/16036413-e526-43c0-9d1a-21eaf9f03ad8)
![image](https://github.com/user-attachments/assets/a2d6a664-a38f-4b04-bf6d-9ef5127168ea)
![image](https://github.com/user-attachments/assets/b0a18c8b-60de-4448-8981-f6aea7c22f4d)
![image](https://github.com/user-attachments/assets/4f8feb25-08cb-42b5-b990-ae18514d949f)
![image](https://github.com/user-attachments/assets/e98c9d2d-f418-40dc-ae35-6379d4b10df5)

* [Question]
* Total -> 16
* a + b + c + d = 16.

![image](https://github.com/user-attachments/assets/79bb907f-c784-4859-aab3-65099c6edebc)

* a = d -> Odd no.
* b = c -> Even no -> more than '2' plots.

![image](https://github.com/user-attachments/assets/ffb3bedf-a9f5-4d08-9973-ec63f2f0e880)
![image](https://github.com/user-attachments/assets/756cc7ee-3998-4454-880a-7e4b999e537c)

* '3' is not an even number.

![image](https://github.com/user-attachments/assets/22da94f3-0814-4e7e-b1ed-aacfa621f9cd)

* Between 'b and c' we have '4 and 6' and vice-versa.
* Trees -> 304.
* a = d = 3.
* b = c = 4/6

![image](https://github.com/user-attachments/assets/803d6038-7c14-4731-a892-1727d744457b)
![image](https://github.com/user-attachments/assets/94706de2-2044-4861-ad75-ca79a8433f49)

* Attacking points -> Positioning of Plots -> 3,7,8,10,11.  
* In the 1st point, **order** is there which is **descending order**.
* In the 2nd point, **order** is not there.

![image](https://github.com/user-attachments/assets/ad8cde78-1015-4c2e-8485-7fbe1fd152a9)

* B = 2 + C.
* B = 6, C = 4.

![image](https://github.com/user-attachments/assets/c516f381-5d89-40da-880f-05422e5e6caf)
![image](https://github.com/user-attachments/assets/66f85fd1-1dc5-493f-a346-b25c5bdd3b31)
![image](https://github.com/user-attachments/assets/bd519b63-dbcc-4c44-9b8e-bf0d4134d972)

* 'D' has to fill in '4th row'.
* Keeping 'b' at '3rd row 3rd column'. [Let]
* Keeping 'c' at '2nd row 2nd column'. [Let]

![image](https://github.com/user-attachments/assets/bc0ed1c7-d823-4a79-b876-c8f588a164b4)

* We are getting adjoining plot of 'c' in row '2' but we are given that adjoining plot of 'c' will come in either '1,3,4'. So adjoining plot of 'c' in row '2' is **not possible**.
* 'B' cannot happen in '3rd row 3rd column'. 'C' will happen in '3rd row 3rd column'.

![image](https://github.com/user-attachments/assets/15f22f04-02b9-45de-af55-894b7ccc7be8)
![image](https://github.com/user-attachments/assets/f6bc18f8-3d70-4737-ac1c-530df5df701f)
![image](https://github.com/user-attachments/assets/d2307e77-4c79-4d4c-a39e-c18c87d4bed6)

* Point **11** -> Adjoining column is also **not possible**.
* 'A' is done '3' times.
* 'D' is done '3' times.
* 'C' is done '4' times.

![image](https://github.com/user-attachments/assets/270d04fe-0ef9-4131-8cfe-c56d5b22c657)

* 'B' is left.

![image](https://github.com/user-attachments/assets/61c74db4-d7cc-46b5-93ee-f0049c972e93)

* We got the **positioning**.

![image](https://github.com/user-attachments/assets/ff4b7a1a-bcf8-4265-9f73-2a61d935abde)
![image](https://github.com/user-attachments/assets/5ae3a6f1-b2aa-449b-b57a-7834cd8f117f)
![image](https://github.com/user-attachments/assets/924fe337-5b04-4efd-969b-ce1063a45930)
![image](https://github.com/user-attachments/assets/33cb1b86-c4c8-403b-aa31-8bdb95e4d969)

* Multiples of '4' -> 16 + 12 + 8 + 4 -> 40.
* Odd multiples of '5' -> 5 + 15 + 25 + 35 -> 80 -> We don't know their order.
* 2nd col - 4th col -> prime no.
* p1 + p2 + p3 + p4 = 54 -> Prime nos.

![image](https://github.com/user-attachments/assets/691b80e4-e5c9-43aa-bafa-9a0b8b1301e5)
![image](https://github.com/user-attachments/assets/e53ea788-a096-43e7-af19-76f5ad226a91)

* 1 + 7 + 13 + 19 = 40.
* '1' is not a prime no.
* We have to make the '40' into '54'. We need '14' extra.

![image](https://github.com/user-attachments/assets/15465bd7-4dcd-4a34-aa8f-6d3c3212e30e)
![image](https://github.com/user-attachments/assets/86de6fcb-4219-4b97-8780-c541312c5390)

* Put '1' row again as constant.

![image](https://github.com/user-attachments/assets/5685ed56-0e61-4b39-802d-caf135563d43)
![image](https://github.com/user-attachments/assets/c4a4bd46-5aa6-4dc5-9549-e78837400ede)

* Prime nos -> 11, 17, |-7|, 19.
* Sum -> 11 + 17 + |-7| + 19 -> 54.

![image](https://github.com/user-attachments/assets/e1bc4cfe-faee-41d4-bbc4-9717379c88ab)

* Sum of 'C' -> 81.
* C -> 16 + 8 + 17 -> 41
* 81 - 41 -> 40.
* 2nd Row -> CBDA -> 40 + 12 + 7 + 5 -> 64.

![image](https://github.com/user-attachments/assets/18e4ab02-58aa-4901-8825-dbaed21108b0)

* G = 64.
* G = P - 18.
* P = 82.
* G = A - 36
* A = 100.
* M = 304 - (100 + 64 + 82)
* M = 58. [1] [Answer]

![image](https://github.com/user-attachments/assets/2af141f3-44e5-4f13-8ff7-42625af9f82f)
![image](https://github.com/user-attachments/assets/c3765c6e-633a-4c1f-ad56-00c2537dbc15)

* IMPORTANT to attack the set from the positioning part. [**IMPORTANT**] [Logic] [Concept]

![image](https://github.com/user-attachments/assets/146d1c6b-27d6-46cd-a385-7d3fb12de72b)

* A -> 30 + 5 + 28 -> 63. [3] [Answer]
* B -> 19 + 35 + 12 + 32 + 25 + 4 -> 127.
* D -> 7 + 11 + 15 -> 33.
* Max. trees in a plot -> 40. [2] [Answer]
* Who -> C. [2] [Answer]
* Max. Apple trees -> B. [4] [Answer]
* Diff -> B - D -> 127 - 33 -> 94. [5] [Answer]

![image](https://github.com/user-attachments/assets/d1ac766c-d83d-4a6d-9143-3f5fe1778930)
![image](https://github.com/user-attachments/assets/f7d1f6e2-109c-4b9c-ac9f-34cd0c3598ae)
![image](https://github.com/user-attachments/assets/6fe5d847-e8ed-41b5-a355-e824efedbe54)
![image](https://github.com/user-attachments/assets/c3611bdb-240c-4fea-9530-f5000b1687f5)
![image](https://github.com/user-attachments/assets/27ff5036-a85e-4093-a167-89bb4b285fad)

* [Question]
* Amt. are in **1000s**.

![image](https://github.com/user-attachments/assets/10072d22-04d3-4a5c-b065-ca304f7c07aa)

* Example.
* Attacking point -> Min/Max.
* D/A -> Smaller values -> Less no. of cases.
* Out of '120', 'D' has '75' at the end.

![image](https://github.com/user-attachments/assets/0b7844fd-3766-4f81-abe0-7bcaf81f4460)

* D -> 120 -> Lowest.
* D -> 75 left -> Highest.
* D -> 120 - 75 -> 45 spent.
* D <= 45.
* Till item '9', 'D' has spent only '<=45' as 'D' is left with '75' to bid on item '10'. [Logic] [Concept]
* 'D' must be left with '75' as 'D' bid '75' on 'item 10'. So 'D' has spent '45'.
* 68 > 45 -> We want less than '45'.
* 'D' did not spend '68' on 'item 8'.

![image](https://github.com/user-attachments/assets/f436cf22-df97-4c26-b488-71cc54a40b94)

* Item '1' winner -> Could be either 'B' or 'D'.

![image](https://github.com/user-attachments/assets/3ccda836-6489-4717-a43e-d087cdad2ac7)

* Item '2' winner -> 'C', 'B' or 'A'.
* Item '3' winner -> 'E' or 'A'.
* Item '5' winner -> 'D' guranteed.
* As 'D' is suppose to spend less than '45' and 'D' has spend '40' on Item '5' guranteed, which means that 'D' has not spend anymore money.
* 40 <= 45.
* 'D' spent '40' on item '5' and cannot spend anymore till item '9'.
* We don't know about Item '10' yet but till Item '9', 'D' has only bought/spent on Item '5'.

![image](https://github.com/user-attachments/assets/014f68d3-bffd-42ed-893e-d13909d48b13)

* Remove 'D' eveywhere other than Item '5'. 

![image](https://github.com/user-attachments/assets/d004d098-94b0-4cd1-b233-37efc2eaa3e9)

* Item '6' -> 'A or E' -> Cannot be 'D'. 

![image](https://github.com/user-attachments/assets/52791ce0-d73d-49a4-bd23-44ecb630c240)
![image](https://github.com/user-attachments/assets/19a7a09f-ad38-4638-a33c-4cff357a0e26)

* Item '9' -> 'D or C' -> Cannot be 'D' -> 'C' guranteed.
* We don't know about Item '10'.

![image](https://github.com/user-attachments/assets/605d34fc-0fa7-4303-a6fc-d70ca8f1be8e)
![image](https://github.com/user-attachments/assets/d0019488-d7f8-4879-adf6-5c20381f0496)

* Attacking point -> Who are coming more no. of times -> 'C', 'E'. [Logic] [Concept]

![image](https://github.com/user-attachments/assets/f5d23d60-a37f-49ab-8ad7-91a6b1bfefa1)
![image](https://github.com/user-attachments/assets/4503c603-6925-4c4c-90ee-d04921bbeaea)
![image](https://github.com/user-attachments/assets/bda69517-e345-4e0f-a874-1b9996917324)

* C -> 218.
* 'C' has spent till item '9' -> 218 - 74 -> 144
* C <= 144.
* 'C' can spent '144'.
* For items '4 and 9', 'C' is the winner.
* Item '4' -> C >= 33.
* Item '9' -> C >= 35.

![image](https://github.com/user-attachments/assets/69c2e554-fb25-4c47-9825-805635d9b6de)
![image](https://github.com/user-attachments/assets/a19e492d-9376-474e-9b8d-8d0a45dacfc4)

* 'C' left -> 144 - 33 - 35 -> 76

![image](https://github.com/user-attachments/assets/78a42a1a-dc4d-4487-8add-598fdf835680)

* E -> 143.
* 'E' has spent till item '9' -> 143 - 70 -> 73
* E <= 73.
* 'E' can spent '73'.
* For items '3,6,7 and 8', 'E' is the options.
* For item '8', 'E' has bid '74' but 'E' can bid a max. of '73'. So 'E' is not in item '8'.
* Item '8' belongs to 'C' then.
* 'C' left -> 76 - 75 -> 1. [Min. '75' as '74' is already there]

![image](https://github.com/user-attachments/assets/890f5a52-790c-419e-af08-d4fc48386ecf)
![image](https://github.com/user-attachments/assets/d067b632-e696-438c-9a56-211a582dba8c)
![image](https://github.com/user-attachments/assets/76a71bfe-a8ce-44d9-8e11-e416a57080d1)

* 'C' cannot buy anymore items.

![image](https://github.com/user-attachments/assets/41bcf992-c195-49a4-862e-4ad8811a5e4d)
![image](https://github.com/user-attachments/assets/59eed735-812c-4349-9d3b-c967af4334f5)
![image](https://github.com/user-attachments/assets/a8bd866b-413a-4180-8616-b51ecafd944a)
![image](https://github.com/user-attachments/assets/826e9644-d444-4d7f-8176-c2f288653bc4)

* 'E' got item '7' -> >= 37.
* 'E' left -> 73 - 37 -> 36.

![image](https://github.com/user-attachments/assets/1f1ca9e4-91be-4745-b237-2b7350e5e296)

* In item '3 and 6', we have confusion between 'A and E'. Attack item '3 and 6'.

![image](https://github.com/user-attachments/assets/bfe8f510-16eb-4062-b9bc-39a8f1f3dde6)

* A -> 121.
* 'A' has spent till item '9' -> 121 - 69 -> 52.
* A <= 52.
* 'A' can spent '52'.

![image](https://github.com/user-attachments/assets/681511d5-3b44-4b99-95d3-83254304a5bf)

* 'E' cannot take a bid of more than '36'.
* Item '3' -> >=42.
* 'E' cannot take a bid of '42'. So 'A' gets Item '3'.
* 'A' got item '3' -> 42. [Given in table already]
* 'A' left -> 52 - 42 -> 10.

![image](https://github.com/user-attachments/assets/066c67fd-bcc3-46de-a3f0-a8848c10478a)
![image](https://github.com/user-attachments/assets/0f2dd9cf-7c8d-47e1-ab7a-c1b18a882147)

* 'A' cannot buy anymore items.

![image](https://github.com/user-attachments/assets/3a126667-bff7-4b07-a0e5-fcc6b1153837)

* We are left with item '10'.
* 'B' spent on item '1' -> >= 25 -> min. of 25.
* 'B' spent on item '2' -> >= 37 -> min. of 37.
* 'D' spent on item '5' -> 40.
* 'E' spent on item '6' -> 42.

![image](https://github.com/user-attachments/assets/bd08abaa-a9a0-4fb3-97b7-1c4caf6208e5)
![image](https://github.com/user-attachments/assets/72ae652f-53eb-4b94-b74c-81fb7ce8956e)
![image](https://github.com/user-attachments/assets/11a9ef2f-1b31-4e23-8539-b5fae668a7f8)

* 'D' total -> 120.
* 'D' spent -> 40 on item '5'
* 'D' left -> 120 - 40 -> 80 for item '10'.
* 'B' total -> 136.
* 'B' spent -> 25 and 37 on item '1 and 2' -> 62.
* 'B' left -> 136 - 25 - 37 -> 74 for item '10'.

![image](https://github.com/user-attachments/assets/8122bf52-08f9-4722-8d04-70d7b14bd7d4)
![image](https://github.com/user-attachments/assets/bb19f694-9f45-41fa-87c6-c322ecdb6f01)

* 80 > 74 -> 'D' wins the bid for item '10'.
* Attacking points. [Concept] [Logic] [**VERY IMPORTANT**]






   










## Practice Tests 

![image](https://github.com/user-attachments/assets/0a482ca8-7c94-45a4-b024-dda4fad9eaaa)

* [Question]
* Have chutney -> 3
* Not having chutney -> 3
* Total -> '2' are odds and '4' are even.
* '2' odds -> Not having chutney.
* '3' Not having chutney -> '2' odds and '1' even in total.

![image](https://github.com/user-attachments/assets/df840a9f-190d-4ba3-8be3-359f1e9c3368)

* If we take '2' for ankur in vada then we have to take '4' for sajal in samosa but that is not possible because '4' is already taken by ankur in samosa. This is **not possible**.
*  We take '0' for ankur in vada and '2' for sajal in samosa. This is the **only possibility**.

![image](https://github.com/user-attachments/assets/42b8c24d-9143-4c44-9a5d-2c11434c30fc)
![image](https://github.com/user-attachments/assets/764a0ddf-9313-4abb-8147-8391945a0258)

* We have found '1' even no. not having chutney, so the rest even no. are having chutney.
* If someone eats '1' vada then pawan will eat '2' samosa. This is not possible because '2' is already taken in samosa. 
* If someone eats '2' vada then pawan will eat '4' samosa. This is not possible because '4' is already taken in samosa. 
* If someone eats '3' vada then pawan will eat '6' samosa. This is possible because '6' is not taken in samosa. 

![image](https://github.com/user-attachments/assets/0a058a52-9989-48d4-a789-5819c2571a1a)

* We don't know who is having '3' vada but we know that pawan is having '6' samosas.

![image](https://github.com/user-attachments/assets/8d0f0074-ed74-49af-9d9e-c82b7a60e7b0)

* We know that with '5' samosa, '3' vada is going to go.
* 5 + 3 -> 8.
* We are left with '3' samosa and it can go with either '2 or 3'.
* We also need '2' odd numbers.
* Pawan cannot have '3' vada then it will be '6 + 3 -> 9' which is the max but rishi wants the maximum.
* Pawan cannot have '2' vada as well then it will be '6 + 2 -> 8' which is equal to the max i.e '8' but rishi wants the maximum. We cannot have '2' maximums. 
* Pawan can have '1' vada then it will be '6 + 1 -> 7'. This is **odd** as well. So **no chutney** for pawan. [2nd odd no.]
 
![image](https://github.com/user-attachments/assets/b387897e-2f45-4c5e-9f6a-6a1e60c5ee82)
![image](https://github.com/user-attachments/assets/f1746093-ad3d-4539-8c1f-79fab9182da6)
![image](https://github.com/user-attachments/assets/6bdc1b36-45ff-4454-b98d-4dc90d1ce61b)

* Rishi -> max -> 5 + 3 -> 8.
* Different between vada and samosa, who eat chuutney:-
* Sajal -> 4 - 2 -> 2.
* Ankur -> 4 - 0 -> 4.
* Rishi -> 5 - 3 -> 2.

![image](https://github.com/user-attachments/assets/4cff51a3-363e-4db0-aacb-ee37a1afdae1)

* Answer -> option **A** -> 8. [1] [Answer] [Solution] [**VERY IMPORTANT**] [Practice]
* Answer -> option **C** -> 4. [2] [Answer] [Solution] [**VERY IMPORTANT**] [Practice]
* Answer -> option **B**. [3] [Answer] [Solution] [**VERY IMPORTANT**] [Practice]

* Rishi & Om -> 8 + 6 -> 14.
* Om & ankur -> 6 + 4 -> 10.
* Pawan & Sajal -> 7 + 6 -> 13.
* Rishi & Pawan -> 8 + 7 -> 15.

* Answer -> option **D**. [4] [Answer] [Solution] [**VERY IMPORTANT**] [Practice]
* Answer -> option **C** -> 4. [5] [Answer] [Solution] [**VERY IMPORTANT**] [Practice]

![image](https://github.com/user-attachments/assets/1bb30ccb-a6ed-470f-ace9-5c0b54c3f154)
![image](https://github.com/user-attachments/assets/9b971a6d-3ce6-4206-94a6-8fec5d49cf0b)
![image](https://github.com/user-attachments/assets/3ec156f0-1052-477e-90cf-d0d7414ecfa7)

* [Question]
* Odd(O) + Odd(O) -> Even(E). [Formula] [**IMPORTANT**]
* Even(E) + Even(E) -> Even(E). [Formula] [**IMPORTANT**]
* 1st column -> 1 -> Odd no. case.
* 2nd column -> 1/3/5.
* 1st column -> 2 -> Even no. case.
* 2nd column -> 2/4/6.

![image](https://github.com/user-attachments/assets/457d1f14-9a28-4d42-80ca-30cc4a0b68a6)
![image](https://github.com/user-attachments/assets/79ac8a5a-7e12-45cf-9c79-c6580e5979f6)

* As 'w = 3' so 'MC' cannot have '3' then 'u = 6' is also not possible.
* For 'w' in desert it can be '5 or 6' but 'w' in 'MC' is '3' which is an odd no. so we have to keep an odd no. for 'w' in desert which is '5'.
* So 'u' cannot have a '5' in desert which means that 'v' cannot have a '2' in 'MC'. 'u' is left with '4' only. So, 'u = 4'.

![image](https://github.com/user-attachments/assets/8a9d0413-d3a0-41c7-a6bc-a064b33a6b23)
![image](https://github.com/user-attachments/assets/32ddc2e9-04ae-4752-9d9b-906c24edaf81)

* 'x' can have '1 or 2' but 'v' already has '1' in 'MC'. So 'x = 2'.

![image](https://github.com/user-attachments/assets/8bc0429b-116c-40a4-96f4-53d76de4e521)
![image](https://github.com/user-attachments/assets/e22c298c-d183-436f-b12a-5a8ca555c4d6)

* As 'x = 2' which is an even no. so 'x' in desert has to be an even no. only. So it can be '2/4/6'. '4' is already taken by 'u' in desert. If 'x = 6' then that is the best possible value in deserts then how is "x's score less than that of 'S' in desserts" is possible? from point **4**. So 'x = 6' is not possible. Then,
* x = 2.

![image](https://github.com/user-attachments/assets/d3886073-798e-46dd-9bac-457a2a69cc34)
![image](https://github.com/user-attachments/assets/b6e7517a-feeb-493a-8f24-58b9f2e5adf1)

* Possible values of 's' -> 1,3,6.
* 'S' has to have more than 'x' in desert so 's = 1' is not possible. 's' can be either '3 or 6'.

![image](https://github.com/user-attachments/assets/80fca904-424c-456f-bb77-c823aba70991)
![image](https://github.com/user-attachments/assets/bcda3b2c-e074-4fec-a362-c88b6c03e12a)
![image](https://github.com/user-attachments/assets/dea5155f-b2a3-44a6-8349-246c743aae55)
![image](https://github.com/user-attachments/assets/57f84647-109c-48a0-a6cc-57149fbdfbc3)
![image](https://github.com/user-attachments/assets/a24d67e0-0e3f-43eb-bc8c-dc2b69d3290c)

* U -> 4 or 6.
* 'u' cannot have '4' because if we keep 'u = 4' then we are left with '5 or 6' for 's and t'.
* In both the cases 's' will have a higher score than 'u'. This is going to violate the condition of point **5**. 'u = 4' is not possible. So,
* u = 6.

![image](https://github.com/user-attachments/assets/d457ab52-6527-458d-8687-8f66b5f0a825)

* We have '2' possibilities for 't and v' when it comes to '1 and 3'.

![image](https://github.com/user-attachments/assets/33c7f264-4e05-43cd-b56c-5596338164ff)
![image](https://github.com/user-attachments/assets/bef3db18-e604-4232-bc46-43bf83e2df37)

* '6' is not possible for 'u' in starters.
* 'u = 5' in starters.
* For 'x' -> E + E + O -> O.

![image](https://github.com/user-attachments/assets/316e6e55-2dd3-4308-bc64-4c4baac555a0)
![image](https://github.com/user-attachments/assets/3e7e8267-114d-4fdd-b7b9-0678330869da)
![image](https://github.com/user-attachments/assets/e0059ca4-2d97-4109-8919-0154532383a4)

* 't' cannot be '1'. 't' has to be '3' in desert.
* 'v' has to be '1' in desert.

![image](https://github.com/user-attachments/assets/3be9c3ef-90d4-4379-accc-ea20798b6ada)
![image](https://github.com/user-attachments/assets/1eb2baf1-b48b-4107-8e81-d0c921c3e387)
![image](https://github.com/user-attachments/assets/8b1954f8-e2ab-486e-90ab-678f5df6b7e9)
![image](https://github.com/user-attachments/assets/be2d14b7-ed72-4f18-96d1-f858ab05a332)

* V -> 1 + 1 + 3 -> 5
* x -> 2 + 2  + 1 -> 5.
* Overall score of everyone should be **distinct** but we are gettinng '2' 5s. So this is not possible.

![image](https://github.com/user-attachments/assets/5a16c01c-db6e-423c-bbaa-1af3ff74ad0a)
![image](https://github.com/user-attachments/assets/228d3878-0df1-46b4-b535-752c5b479b2b)

* Possible combinations.
* '1' combination -> Highlighted by Yellow.
* '2nd' combination -> Highlighted by Green.

![image](https://github.com/user-attachments/assets/15f15aa8-3d11-427e-ad99-e922996a5456)

* S -> Yellow -> 6 + 4 -> 10.
* S -> Green -> 3 + 5 -> 8.
* U -> 4 + 6 -> 10.
* Not always.

![image](https://github.com/user-attachments/assets/dee1f852-1427-43ef-b538-f8a14d53a907)

* can be True -> Possibility.  [Formula] [**IMPORTANT**]
* is/are False -> 100% guranteed.  [Formula] [**IMPORTANT**]
* T -> Green -> 6 * 2 + 4 -> 16.

![image](https://github.com/user-attachments/assets/9e22e5ed-6396-4b0b-a4e4-ee68370051b8)

* option **3** -> 'u' is always the highest?
* It is always True?

> **No**. 'u' has a fixed score of '15'. With green 'T' is the highest and with yellow 'S' is the highest. 

![image](https://github.com/user-attachments/assets/96a9773f-644d-45f0-b97d-1368f4070c57)
![image](https://github.com/user-attachments/assets/58ca2c6d-5860-4a51-aeb0-0a1353bc17a5)

* Answer -> 15. [1] [Answer] [Solution] [**VERY IMPORTANT**] [Practice]
* Answer -> 18. [2] [Answer] [Solution] [**VERY IMPORTANT**] [Practice]
* Answer -> True. [3.1] [Answer] [Solution] [**VERY IMPORTANT**] [Practice]
* Answer -> False. [3.2] [Answer] [Solution] [**VERY IMPORTANT**] [Practice]
* Answer -> True. [4.1] [Answer] [Solution] [**VERY IMPORTANT**] [Practice]
* Answer -> True. [4.2] [Answer] [Solution] [**VERY IMPORTANT**] [Practice]
* Answer -> option **3**. [5] [Answer] [Solution] [**VERY IMPORTANT**] [Practice]

![image](https://github.com/user-attachments/assets/2aef8b32-89d3-4f54-98ce-0416aa21d2c1)
![image](https://github.com/user-attachments/assets/e0518834-ce3c-4692-946d-fc24fcc2337b)

* [Question]
* Slots -> 5months * 2dates -> 10.
* Q and R -> same month exam.
* Pri -> Prime nos.
* '3' people between 'u and v'.

![image](https://github.com/user-attachments/assets/1f0ccb56-29dc-4e00-80f5-5b14d31b90e1)

* '4' people between 'p and q'.
* '3' people between 'r and s'.
* T and S -> consecutive months.

![image](https://github.com/user-attachments/assets/d9bf53af-2664-4bf5-8590-b0abd27f9d60)
![image](https://github.com/user-attachments/assets/cbe0641e-cd78-4111-a73f-0bc7cc0f1559)

* April sum/total -> 125.
* Curly brackets -> One of them/either of the values.
* Square brackets -> sum/total.
* p -> x -> y.
* 'y' is appearing after 'x'.

![image](https://github.com/user-attachments/assets/5476ab9e-9435-4ad9-a2b6-1bd675f60ca2)
![image](https://github.com/user-attachments/assets/aa66d3e8-c8f8-4e1a-90f2-fe2ec387685c)

* p = 79 -> pri -> prime number.
* If we put 'p' on 28th of dec or 29th of dec then we cannot put 'x and y' which come after 'p'. We cannot put 'p' there.
* 'p' will be on 28th of may or 29th of may.

![image](https://github.com/user-attachments/assets/d2efaa32-3df8-4c7e-836d-2dba93f71014)
![image](https://github.com/user-attachments/assets/4d75f20a-ac01-4b57-a972-0636d2e2b025)

* Q and R gave exam on consecutive days -> they have to be on the same month.

![image](https://github.com/user-attachments/assets/10a132e5-0fbc-4105-9366-9dd3065196d3)
![image](https://github.com/user-attachments/assets/5da3bc50-67bd-4430-9abf-fb8a9d4b6c69)

* From 30th of nov where 'R' is, if we got '3' places up to place 's', there is already 'p' present, so this case is not possible.

![image](https://github.com/user-attachments/assets/6476e473-3da4-4fe0-bc34-61db92e8ab27)
![image](https://github.com/user-attachments/assets/34d0b4d7-5324-45a6-b765-e2ace65ec760)
![image](https://github.com/user-attachments/assets/5e6a5a7c-31ca-4fed-9ec2-437a080b835d)

* p = 79. [Given]
* t = 71.

![image](https://github.com/user-attachments/assets/4a8e96db-8925-4a75-a339-107467ad91f9)
![image](https://github.com/user-attachments/assets/6e533092-ccf9-4d1e-824d-a42993a53aa1)

* This 'u and v' position is not possible.

![image](https://github.com/user-attachments/assets/abff4e46-4999-420d-9b59-99b9a488261d)

* This 'u and v' position is not possible.

![image](https://github.com/user-attachments/assets/1016d196-f236-432f-aa87-844e85674608)
![image](https://github.com/user-attachments/assets/e5b7d6dc-9130-441d-9a62-009a889fe53e)

* This is the only possibility for 'u and v' position/place.

![image](https://github.com/user-attachments/assets/3f9c6f1c-1597-40d2-8627-62bc3d86d006)

* Below 'p' there is only '2' vacant slots. We need to place 'x and y' after 'p'. We will use those '2' slots to do so.

![image](https://github.com/user-attachments/assets/624e1c76-7dad-4f8f-a4a3-29d52586d773)

* x -> 66 -> even.
* y -> 70.

![image](https://github.com/user-attachments/assets/88f8fa46-fe25-463f-9c76-c48ce279c2dd)

* 'w and u' -> appear on alternate months.
* 'w' has to come in the month of april as there are no dates/months left.
* If 'u' is in april then 'w' cannot come in april as there are no dates/months left. So, 'u' cannot be in april.
* u -> 30th of june.
* w -> april.
* v -> april.

![image](https://github.com/user-attachments/assets/e8eb4b9a-9c36-4020-879f-7cbc4aeba659)
![image](https://github.com/user-attachments/assets/90b4d2ed-5524-435a-bb75-f21227091a4c)
![image](https://github.com/user-attachments/assets/748c6890-23cd-4563-a961-e7903e884cbc)
![image](https://github.com/user-attachments/assets/3dcd7989-dc8f-474f-9927-888b92b02c2a)

* t -> 71.
* v -> 4 + t -> 4 + 71 -> 75
* v -> 75.
* total of april -> 125.
* w -> 29th of april -> 125 - 75 -> 50.

![image](https://github.com/user-attachments/assets/6dbc6c70-08f3-4e5b-addd-aa5113a67be6)
![image](https://github.com/user-attachments/assets/84ac729f-c00f-4e3f-abb8-ae38cd8011f1)

* R -> 31 days in dec -> should be a prime number.
* 'r' is between '71 to 79'.
* '73' is the only prime number between '71 to 79'.
* r -> 73.

![image](https://github.com/user-attachments/assets/68696241-02b8-4ee7-94c6-b36de30b66b7)

* 's' is between 't and r' which is between '71 to 73'.
* s -> 72.
* 67 -> prime number.
* Q -> 31 days in dec -> should be a prime number -> 67.
* u -> 60.

![image](https://github.com/user-attachments/assets/cad47ab9-dd22-460f-9643-c3db6db95fdd)
![image](https://github.com/user-attachments/assets/4e327820-a5d0-4075-bbe7-fcebe9b18029)
![image](https://github.com/user-attachments/assets/2fdbdf72-846d-4677-b1a7-17f1afaee2fc)
![image](https://github.com/user-attachments/assets/d97ad1af-080e-4e12-a920-452ad37e8712)

* w,y,r,s ->
* w,y,s -> non-prime nos
* r -> prime no -> odd one out.
* x -> 66
* After 'x' -> y,q,r -> 70,67,73 -> '3' people marks > x i.e > 66.

![image](https://github.com/user-attachments/assets/b99564d8-01a0-4957-9c3b-a20f7cb7d075)
![image](https://github.com/user-attachments/assets/be15c8f7-d1bd-4c5c-a68a-97860744b904)
![image](https://github.com/user-attachments/assets/ed3a43b4-e7ec-4aaf-b7b1-01306eacc0c3)

* Answer -> S. [1] [Answer] [Solution] [**VERY IMPORTANT**] [Practice]
* Answer -> 75. [2] [Answer] [Solution] [**VERY IMPORTANT**] [Practice]
* Answer -> R -> option **3**. [3] [Answer] [Solution] [**VERY IMPORTANT**] [Practice]
* Answer -> 3. [4] [Answer] [Solution] [**VERY IMPORTANT**] [Practice] [Doubt]
* Answer -> 70. [5] [Answer] [Solution] [**VERY IMPORTANT**] [Practice] 

![image](https://github.com/user-attachments/assets/306f8109-02fa-43b1-90a1-d6fa725328c9)

* [Question]
* Age  for all '6' of them add upto '60'.
* marbles for all '6' of them add upto '60'.
* money for all '6' of them add upto '60'.

![image](https://github.com/user-attachments/assets/12817008-11aa-456e-b4df-1a69cb36cd9a)

### AP
* 4 - 2 -> 2
* 6 - 4 -> 2
* 8 - 6 -> 2.
* 2 -> common difference(d).

![image](https://github.com/user-attachments/assets/16b9224f-9381-47ee-8321-480a1ba65777)
![image](https://github.com/user-attachments/assets/c05b2cfb-17b4-49f8-9454-309acfc9f664)

* It is always a good idea to minimize the no. of variables.

![image](https://github.com/user-attachments/assets/9c02502a-3bb7-45e7-9401-c33321cef906)
![image](https://github.com/user-attachments/assets/852cd54f-3d82-43dd-b6e3-9986d10ca15d)

* No. of terms -> odd(3,5) -> common difference(d) is **d** and start with the value of 'a'.
* No. of terms -> even(4) -> common difference(d) is **2d** and start with the value of '(a - d)'.

* 5 -> odd.
* d = 2. [Given]

![image](https://github.com/user-attachments/assets/ad564227-9e1b-4c86-ab5d-6b0a89d0ec65)
![image](https://github.com/user-attachments/assets/3b44f6de-e324-44ce-b655-88e44127622d)

* Larry = Jeff = a.
* Sum of the ages of everyone -> 60.

![image](https://github.com/user-attachments/assets/029e0953-3ee3-4dd8-b57d-163600358c9f)
![image](https://github.com/user-attachments/assets/24db1226-dc5b-4c4e-9da1-2c90e3326a6c)

* a = 10.

![image](https://github.com/user-attachments/assets/67922bc6-2d5a-4791-940e-22c93534f0ae)
![image](https://github.com/user-attachments/assets/a3a63bc2-884f-455a-9eb7-237a84c80a31)

* L -> middle term.

### GP

![image](https://github.com/user-attachments/assets/c789537e-bbea-4032-854a-1e59bcf8e590)
![image](https://github.com/user-attachments/assets/5972a2ca-1d1e-44de-94a8-6df4ac80576b)

* Common ratio(r).

![image](https://github.com/user-attachments/assets/724a0020-f676-48e9-8662-da3357f54f91)

* E -> middle term.

![image](https://github.com/user-attachments/assets/f710e870-0bc6-4504-8bd8-f0a64a0fa592)
![image](https://github.com/user-attachments/assets/e381ad85-e9d5-4759-992e-bbab91065070)
![image](https://github.com/user-attachments/assets/53c9c547-5b62-4f2b-b002-373bc43b52cc)

* All '3' of them are prime nos -> M,E,S -> All of their sum is '34'.
* All '3' of them are prime nos -> J,L,B -> All of their sum is '34'.
* Total no. of marbles -> 60.
* J,L,B -> Sum is '26'.
* 60 - 34 -> 26.

![image](https://github.com/user-attachments/assets/e784aa1b-e1d1-4964-8435-08cadb8de5eb)

* Total sum of money -> 60.
* s,e,m -> Sum is '26'.
* 60 - 34 -> 26.

![image](https://github.com/user-attachments/assets/355cd4bb-84f0-4578-95d7-617acba5a5d9)
![image](https://github.com/user-attachments/assets/b6f4daf4-da56-4bb8-97e2-d4dd447c9b7b)

* '3' nos in GP that add upto '26'.
* '1' is not a prime number.

![image](https://github.com/user-attachments/assets/68ef4f47-e555-49ff-8aad-79a2c301a698)

* Startig with '1' and common different of '2,3,4 and 5'. For '5' the sum was greater than '26' so not possible.

![image](https://github.com/user-attachments/assets/8bec4abf-016f-4f8b-8568-372594d3e489)

* Sum is greater than '26' so not possible.
* We have got only '1' case.
* '3' nos. in GP whose sum is '26' -> 2,6,18.
* L -> middle -> 6.
* E -> middle -> 6.

![image](https://github.com/user-attachments/assets/c3f07b3e-3767-4ece-a322-a0e2351358ca)
![image](https://github.com/user-attachments/assets/8afd93a8-fdca-4376-82c5-d73a7949b47b)

* Sum of '34' in marbles should be coming from '3' different prime numbers.
* Only common possibility is that 'j = 2 and s = 2'. It is because '6' is already with 'l' and '18' is not a prime numbers.

![image](https://github.com/user-attachments/assets/ba30b26a-fb3d-402c-b199-ee7d4f352b93)

* Sum of '3' prime numbers -> 34.
* One of the '3' prime numbers is '2'.

![image](https://github.com/user-attachments/assets/9869795c-5f05-4530-a961-e44852536420)
![image](https://github.com/user-attachments/assets/3040931a-a0b1-457f-924c-71042a5813e2)

* We got '2' combination of numbers.
* '2' is with 'j'. We need '3 and 29' or '13 and 19' for 'm and e'.

![image](https://github.com/user-attachments/assets/48a8c4f4-2640-4d16-9aa3-48fd00e06704)

* m = l + e -> 29 = 6 + 3 -> not possible.
* m = l + e -> 19 = 6 + 13 -> possible.

![image](https://github.com/user-attachments/assets/50ac56fd-752a-42c8-9ea4-bd35a3f5f766)

* No. of marbles is covered.

![image](https://github.com/user-attachments/assets/6a96d2bb-c5ef-462a-b632-4e6b278643bd)

* We got '2' combination of numbers.
* **Harmonic progression(HP)** is the **reciprocal** of **AP**. [**VERY IMPORTANT**] [Formula]
* AP -> 2,3,5
* HP -> 1/2, 1/3, 1/5.

![image](https://github.com/user-attachments/assets/954c536e-cc72-4868-a63c-78087ff1e594)
![image](https://github.com/user-attachments/assets/5cbda684-8956-4258-a552-119224d82baa)

* middle term -> 3.
* 2,3,6 -> They are in HP.

![image](https://github.com/user-attachments/assets/2dae89b2-5c7a-46cf-86fe-1e0fab3c887a)
![image](https://github.com/user-attachments/assets/1a0c6cba-2b91-4456-bece-105c478f32ef)

* middle term -> 6.
* 2,6,13 -> They are not in HP -> This case is ruled out.
* If 'B = 2, L = 3' then 'J = 29'.

![image](https://github.com/user-attachments/assets/4a1d8bae-26a8-4824-a4b5-6a098513af40)

* Mark -> 6yrs old -> Starts with the min. amt. of money.
* If 'M = 2' then 'S = 18'.
* 'E' is occupying '6'. 

![image](https://github.com/user-attachments/assets/1f676a3d-cae7-46c0-bc73-34faa3d18f11)

* 'E' total -> 8 + 13 + 6 -> 27.
* 'B' total -> 18 + 12 + 2 -> 32.
* 'S' total -> 14 + 18 + 2 -> 34.
* 'L' total -> 10 + 3 + 6 -> 19.
* 'M' total -> 1 + 19 + 6 -> 27.

![image](https://github.com/user-attachments/assets/ed1d9d14-636b-40aa-b7ee-ccfb7eae6a9b)
![image](https://github.com/user-attachments/assets/ba229bbd-106e-4bb6-9e0c-fd9901920fde)

* 'm' has the same total as 'e'.

![image](https://github.com/user-attachments/assets/0531ae8b-c8fd-47d3-ad41-88f0e6345018)

* Answer -> 2. [1] [Answer] [Solution] [**VERY IMPORTANT**] [Practice] 
* Answer -> 29. [2] [Answer] [Solution] [**VERY IMPORTANT**] [Practice] 
* Answer -> 19. [3] [Answer] [Solution] [**VERY IMPORTANT**] [Practice] 
* Answer -> 3. [4] [Answer] [Solution] [**VERY IMPORTANT**] [Practice] 
* Answer -> option **4** -> Mark. [5] [Answer] [Solution] [**VERY IMPORTANT**] [Practice] 

### 5

![image](https://github.com/user-attachments/assets/71dac2a1-d1b9-4603-95ee-efdaae8c5c23)

* [Question]
* Ordering set -> It is always better to make the parameter which is the **order** as the principle variable. [Formula] [**IMPORTANT**]

![image](https://github.com/user-attachments/assets/fc097bad-05d7-4984-a51c-3875a11edadf)

* There are '2' different possibilities.
* 'G' receives after 'D' which means that 'G' cannot be in january.

![image](https://github.com/user-attachments/assets/94d78965-339f-4c58-bd3b-0762ad77cd22)
![image](https://github.com/user-attachments/assets/253a797f-6ea8-41d7-8271-557049649630)

* F -> April.
* 'A' cannot in july, so 'A' is in jan.

![image](https://github.com/user-attachments/assets/c9574644-cb43-4aaf-8a43-a48f1a1b4ae8)

* A -> 8.5, then 'E' cannot get '8.5'.
* E = 2
* G = 0.4
* D = 1.7

![image](https://github.com/user-attachments/assets/172419cf-cebf-4709-8c8e-673be295d43c)
![image](https://github.com/user-attachments/assets/3f021ddc-3848-4452-bc41-87587650a079)
![image](https://github.com/user-attachments/assets/f408fc46-0957-43e2-aa9f-828faf01d3c9)

* Take another table for 'C' in june.

![image](https://github.com/user-attachments/assets/d324b91b-616e-448a-94a9-08a929680ae2)
![image](https://github.com/user-attachments/assets/cb8846d1-1664-4b5a-9749-686de1ff767e)
![image](https://github.com/user-attachments/assets/930d8597-720f-4666-8d6f-6eed5ce8284b)
![image](https://github.com/user-attachments/assets/d1a073e6-8ca8-4193-ad92-a7c1cd521bed)

* '0.4' already in may.
* Junee -> 4.
* April -> 0.5 

![image](https://github.com/user-attachments/assets/d1dab1bd-fe02-456a-9a95-f9ef9462e8fa)

* Condition -> B > C.
* Case **1** -> B = 4, C = 3.2 -> 4 > 3.2 -> satisfies condition.

![image](https://github.com/user-attachments/assets/fcf137f3-759c-4702-a387-0d613d199bec)
![image](https://github.com/user-attachments/assets/9f26e76d-e41c-453e-a0bc-336652e1ded8)

* Case **2** -> C = 4, B = 3.2 -> 3.2 > 4 -> not satisfying the condition.

![image](https://github.com/user-attachments/assets/b485013f-606b-44f7-b4b0-b20071b6fb4a)
![image](https://github.com/user-attachments/assets/b772895f-d190-49f7-83ee-47aa80b5fa5b)

* Spu = 1.9M + Pfizer.
* Total dosage -> x + (x + 1.9).

![image](https://github.com/user-attachments/assets/5d3b6ac0-d4ed-407e-b4d1-e141fb6f2e9a)

* Pfizer -> x -> 9.2
* Spu -> x + 1.9 -> 9.2 + 1.9 -> 11.1

![image](https://github.com/user-attachments/assets/82257045-a3c8-48fb-861c-14b6903cef76)

* Pfizer -> given to '3' countries.
* Spu -> given to '4' countries.
* Pfizer -> 2 + _ + _ -> 9.2 -> 2 + 3.2 + 4 -> 9.2

![image](https://github.com/user-attachments/assets/43c98e3e-59f6-4a8c-991e-c7749cbcbfbc)
![image](https://github.com/user-attachments/assets/fb6b86b3-ae48-4c40-bb83-150d7cb7a595)
![image](https://github.com/user-attachments/assets/eb21cbca-e4d2-4fca-823f-2607a0d0b873)
![image](https://github.com/user-attachments/assets/ba969aa4-13dc-4640-ad13-bf68403dd332)
![image](https://github.com/user-attachments/assets/eda724e4-8d26-47f4-b1b7-c0f8d1c89dc6)
![image](https://github.com/user-attachments/assets/cfe5a49f-86d4-4bfc-bd1f-24234a763db4)
![image](https://github.com/user-attachments/assets/d4c4ebbc-361b-4558-92b7-8822c296a2cc)

* option **a, c, d**  -> A, G, E -> all get doses in the months of greater than 30 days.
* option **b**  -> C -> Gets it's dose in the months of less than 30 days.

![image](https://github.com/user-attachments/assets/c0ad3898-94f9-42d8-857b-88e9eef58fa0)
![image](https://github.com/user-attachments/assets/adde505c-fdb3-40ed-ac11-782f7238f538)
![image](https://github.com/user-attachments/assets/f8799715-6e3b-47ec-9071-ba2f8293fd7a)

### 6

![image](https://github.com/user-attachments/assets/9883e157-8b32-4927-9720-46c6242f153a)

* [Question]

![image](https://github.com/user-attachments/assets/941ec05b-a25a-4ee5-98b6-77ac559d22c6)

* Prime factor of '360'.

![image](https://github.com/user-attachments/assets/9152a42f-1877-4248-94d6-6edad97564e0)
![image](https://github.com/user-attachments/assets/5ecb30bd-3ca5-4658-b938-4fa726f287da)
![image](https://github.com/user-attachments/assets/621be0cf-0ad2-461b-a0bd-f6966bf21728)

* Try to get all of the combinations systematically. First complete 'x = 3' and then go for another value of 'x'.

![image](https://github.com/user-attachments/assets/ab71740c-d8f2-4eeb-8d8f-4dc4999158a7)
![image](https://github.com/user-attachments/assets/d073205c-cd82-4953-bb24-d3bbe6b8ebf9)

* Order is not important -> No repeatation allowed. [Formula] [**IMPORTANT**]

![image](https://github.com/user-attachments/assets/96adf539-67cb-432a-86ff-345f9d034b7a)
![image](https://github.com/user-attachments/assets/7a81d053-3bc5-4407-b714-7043f52ad34b)

* Approach is important -> Always go in an order. [Formula] [**VERY IMPORTANT**]

![image](https://github.com/user-attachments/assets/0b505065-ba3c-4645-87a4-3ef83d3a8b51)

* Perfect Square -> 25 -> '2' possibilities.

![image](https://github.com/user-attachments/assets/03ed43c7-2cee-45a8-9a31-90c98b1b8cb3)

* Sum is a Prime No -> 37,29,23,23.
* '2' out of the '3' nos. is a perfect square -> 4,9 -> In '23' -> 4,9,10.

![image](https://github.com/user-attachments/assets/7566c1f4-e418-44ca-bf5a-4126efc4b6c0)
![image](https://github.com/user-attachments/assets/10491ae6-7a45-4f33-93af-b8c2583bb17a)
![image](https://github.com/user-attachments/assets/820d3300-073c-4ec2-99c0-e169cc1ebab9)
![image](https://github.com/user-attachments/assets/96d7241e-a97f-4cf2-b0af-31ef7ad2404d)

* Prime No -> 1 * N.
* Composite No -> A no. that is not a prime no. is a composite number. [Formula] [**IMPORTANT**]

![image](https://github.com/user-attachments/assets/e2adf093-f572-4f71-a2ec-15c6440214d0)

* Composite No -> 22 -> 5,8,9 -> Single digit nos.

![image](https://github.com/user-attachments/assets/3e741fb0-8f70-4823-92b8-30b6d9739e8b)
![image](https://github.com/user-attachments/assets/71e73da0-6fd3-4a99-a8bb-ae10a3378a61)

* '2' out of the '3' nos. is the **same**.

![image](https://github.com/user-attachments/assets/2e822aff-af58-4c6d-a9fe-4ef96485feaa)

### 7

![image](https://github.com/user-attachments/assets/89f95fc3-94e2-46c7-aebd-0c6625c63fc5)
![image](https://github.com/user-attachments/assets/4581e276-1434-41bd-b036-fcff7e16f5ff)

* [Question]

![image](https://github.com/user-attachments/assets/d30435a7-9937-4243-8c93-1f241ce3398f)
![image](https://github.com/user-attachments/assets/d967052e-c4a1-4022-a45e-061dd1843c78)

* y -> Even no. -> we have to do 'y/2'.

![image](https://github.com/user-attachments/assets/65106653-9c6a-42ff-a1af-95e690c2bac5)
![image](https://github.com/user-attachments/assets/87d7a8fd-beed-4549-8419-38f0a43434e0)
![image](https://github.com/user-attachments/assets/ebb70b8b-9c36-4094-a4eb-b8e1abef925c)

* Even house has atleast '1' different type of people. We cannot put '0' anywhere. So, 'y = 2' not possible.

![image](https://github.com/user-attachments/assets/9f125ac6-c619-4829-a8bb-022f6cb2fd57)

* y = 4

![image](https://github.com/user-attachments/assets/54b9d163-5b7c-4f4c-aa8a-0e051026be06)

So, 'y = 6' not possible.
* 11 - (5 + 2) -> 4.
* Senior in '3' is **less than '3'**.
* less than '3' -> 1,2.

![image](https://github.com/user-attachments/assets/0b1a2682-80e5-4cd5-b313-1e523171d3e6)

* '1' is not possible in senior of '3', as we getting '8' in senior of '1'.
* senior of '1' -> Want sum less than 13 -> 2 + 8 + 1 -> 13 -> not possible.
* Senior of '3' -> 2.
* Senior of '1' -> 7.
* Sum of '1' -> 2 + 7 + 3 -> 12.

![image](https://github.com/user-attachments/assets/213d2e94-1bb8-4725-b2a4-75e3911dd444)

* Time in house '1' -> 2 * 5 + 7 * 3 + 3 * 1 -> 34.

![image](https://github.com/user-attachments/assets/995c447f-5fcc-4c15-9655-b157b6166764)
![image](https://github.com/user-attachments/assets/c309e6ea-4398-4f90-b368-9b69d6aae3e7)
![image](https://github.com/user-attachments/assets/e5478505-7074-4439-ba9b-1d3cf4592a95)

* x -> 27.

![image](https://github.com/user-attachments/assets/85c69edd-765f-45f0-8b45-1e3ef3cbf335)

* k -> 15.

![image](https://github.com/user-attachments/assets/b1052117-f659-4dc1-9b95-d9ba6772fb43)

* y -> 25.

![image](https://github.com/user-attachments/assets/4be57779-95e4-4f11-b3be-2da496d51fe0)

* Total time -> 2hr 32mins -> 120 + 32 -> 152.
* 152 - (27 + 25 + 43 + 27) -> 152 - 122 -> 30.

![image](https://github.com/user-attachments/assets/15b4bf42-7a59-499f-bff4-83cdcd04f069)

* House '4' total mins -> 43.
* Used -> 4 * 5 -> 20.
* Left -> 43 - 20 -> 23mins.

![image](https://github.com/user-attachments/assets/59182569-83d1-45f2-82cf-c1916158bd22)
![image](https://github.com/user-attachments/assets/88241aba-e2d9-46f2-a0ae-87640acbd922)

* House '3' total mins -> 30.
* Used -> 4 * 5 + 2 * 3 -> 26.
* Left -> 30 - 26 -> 4mins.
* 4 * 1 -> 4mins.
* b = 4
* a + b = 8.
* a = 4.

![image](https://github.com/user-attachments/assets/e39a8258-3812-476b-b40d-eac87e324599)
![image](https://github.com/user-attachments/assets/9ed1c42c-ff92-460b-9390-4fc8eec284c7)
![image](https://github.com/user-attachments/assets/f48575c2-42be-4fdd-9440-6c28b9fb6dd0)
![image](https://github.com/user-attachments/assets/ce8c7292-3326-4777-adaa-308fb62ed4bd)
![image](https://github.com/user-attachments/assets/5314024f-3b71-4101-a675-4e87ce870ec8)

* 5 * 5 + 3 * 1 -> 28mins. [2]

![image](https://github.com/user-attachments/assets/c428c42b-67a9-4c28-91fa-73ad5eb04978)

* 31 * 1 -> 31mins.

![image](https://github.com/user-attachments/assets/9674ccc4-939c-4fa1-bbb2-7611a7e13e90)

* Baki -> 27 + 43 + 30 -> 100mins.
* Arya -> 34 * 2 + 39 -> 107mins.
* Diff -> 107 - 100 -> 7mins.

## 8

![image](https://github.com/user-attachments/assets/bef0faf1-bf9c-4dbe-880b-c1640fdd7ad9)

* Total -> 72
* Novels distributed -> 9 * 4 -> 36.
* Left -> 72 - 36 -> 36.
* Everyone got **distinct no. of novels**.

![image](https://github.com/user-attachments/assets/75e9202b-1173-428d-9379-c3dc893c0822)

* We are giving '1' extra novel to each one of them.
* Sum of 1st '8' nos -> 8 * 9/2 -> 36.

![image](https://github.com/user-attachments/assets/b20a8a99-899c-47b5-aceb-3cb5a282f8cf)
![image](https://github.com/user-attachments/assets/37f5a3cd-a6f1-47e2-9d0b-fcd330ced5ba)
![image](https://github.com/user-attachments/assets/84752e4a-b889-410f-88d9-077901d9793c)

* A = 2G.
* F = 11. [Fixed]

![image](https://github.com/user-attachments/assets/7d2fb6ff-548f-4a63-b0b2-cfa4cfc6d6bd)

* B - D =  P - C -> 9 - 5 = 10 - 6 -> 4.
* E > 8 -> 9,10,11,12.

![image](https://github.com/user-attachments/assets/0ee2025f-11e4-4ce0-95c8-2de45652fbce)
![image](https://github.com/user-attachments/assets/ab43030d-3636-4f82-87c5-1a045c0e3dac)

* cases -> 9.

![image](https://github.com/user-attachments/assets/89d51f5d-1b4b-4456-a5c1-f85a8d423272)

* Answer -> 5 or 7. [2]
* Answer -> 9. [3]

![image](https://github.com/user-attachments/assets/a22b6bed-2e5b-4c99-a923-d95abdf239f9)
![image](https://github.com/user-attachments/assets/70895a0e-a955-4bd7-a0a4-cfccaf8cf06b)

* Answer -> Both 'a and c' -> option **D**. [4]
* Answer -> A,E,P. [5]

### 9

![image](https://github.com/user-attachments/assets/dfbbf0bc-776a-4c12-b647-ae435fc53754)
![image](https://github.com/user-attachments/assets/8cf24ca8-5eee-49d4-bcb5-bcf7c122bab4)

* [Question]

![image](https://github.com/user-attachments/assets/b352640d-f20a-4864-8679-47df1719ba17)

* x = 160 - a.

![image](https://github.com/user-attachments/assets/16325963-d674-4c46-82f5-55e6b1ae3ae2)
![image](https://github.com/user-attachments/assets/e2eb6455-11c4-4638-baba-bc8241194bc3)
![image](https://github.com/user-attachments/assets/6dc8c441-95d7-44be-9cc2-6784e3c1cf9e)
![image](https://github.com/user-attachments/assets/de6acb96-e141-495b-b59c-1e85c030d862)
![image](https://github.com/user-attachments/assets/b631a7dc-e5fe-4c1a-9803-9864f3ff9d17)
![image](https://github.com/user-attachments/assets/fc6ac819-1195-4782-9a28-357b20c92182)
![image](https://github.com/user-attachments/assets/eaeaa641-d9e1-4a5f-a554-334816f08277)
![image](https://github.com/user-attachments/assets/529ac90a-e4ab-4fd1-b06f-47e6bd78f06a)

* 'a' min -> 47
* 'a' max -> 91

### 10

![image](https://github.com/user-attachments/assets/e107fce7-d417-461e-b2d8-5cadb624a6a8)

* [Question]

![image](https://github.com/user-attachments/assets/78288c80-b4c4-4acd-bdd9-09efe143d828)
![image](https://github.com/user-attachments/assets/cde27b92-0502-43a0-9df6-32760e8728c3)

* common difference(d) -> 3.
* h -> 0.1 + 0.09 -> 0.19
* e -> h + 0.09 -> 0.28
* g -> e + 0.09 -> 0.37

![image](https://github.com/user-attachments/assets/a4c9829b-ef78-4267-8325-20e0ae761385)
![image](https://github.com/user-attachments/assets/ed2d8b92-3299-4122-9772-aa29a52d1ea3)

* f = 0.49.

![image](https://github.com/user-attachments/assets/d7deebbf-c40f-4507-a5dd-8ad726498276)
![image](https://github.com/user-attachments/assets/ff53aa2d-dfe4-43ea-84cc-53d6b56e135b)
![image](https://github.com/user-attachments/assets/55d33d0f-60da-484a-8879-fc79dd5448fa)
![image](https://github.com/user-attachments/assets/9b68d81a-1e56-4333-be76-4b546ee2e0ec)
![image](https://github.com/user-attachments/assets/173a495a-e2f2-43b9-8ecd-65b067a7afb5)

* Filled table.

![image](https://github.com/user-attachments/assets/a2376627-8eaf-413c-b7d2-de3e671108a2)
![image](https://github.com/user-attachments/assets/a2fb15d7-c2b1-4c19-8a00-66302498aa6a)
![image](https://github.com/user-attachments/assets/2b9da22e-fc8f-47c2-9c16-d8e996ba1247)
![image](https://github.com/user-attachments/assets/33b36043-cc01-4242-b025-44d0ca857b99)
![image](https://github.com/user-attachments/assets/bcdef39e-ec17-45d9-a225-ca6b46a4d76e)
![image](https://github.com/user-attachments/assets/7b11933d-c053-4fde-b904-10a744fbe47f)
![image](https://github.com/user-attachments/assets/f6a1951e-daed-46cd-8fb8-b0cf784dd8e9)
![image](https://github.com/user-attachments/assets/1fa1d9ab-9bd4-44a8-8f08-aab12f176234)
![image](https://github.com/user-attachments/assets/008adcdd-64e6-4bfd-8017-35d859fd34bf)

### Venn Diagram

#### 1

![image](https://github.com/user-attachments/assets/6b419907-1d52-44b8-bf47-3da37d0eb45c)
![image](https://github.com/user-attachments/assets/e0c3b50e-0e23-4618-bef8-59294508a342)

* [Question].

![image](https://github.com/user-attachments/assets/57d7ab1d-b684-4cba-8eba-639ce6af5c4e)
![image](https://github.com/user-attachments/assets/c2a1964d-dfb6-4fff-836b-dfdd14ad3ef9)
![image](https://github.com/user-attachments/assets/ed64b546-1aaa-4a6c-beb9-40ee0a8b1be7)

* To avoid the fraction, we will multiply 'a' with '2' so it will be '2a'.
* 2a -> 2 * 2a -> 4a.

![image](https://github.com/user-attachments/assets/1a984042-c50c-4b27-ab6c-9366555d9f97)
![image](https://github.com/user-attachments/assets/d5b05364-941f-41dc-b2ce-2e414674ca44)
![image](https://github.com/user-attachments/assets/248ea03b-a845-4a65-9083-21d857d0118d)

* VA and DI -> 4a + 2a + 2a + x -> 8a + x.
* QA and LR -> 4a + 2a + 2a + y -> 8a + y.

![image](https://github.com/user-attachments/assets/147152a2-1356-45cd-9f8d-e59fe2baa67d)

* Only QA and VA = Only LR and DI = 50.

![image](https://github.com/user-attachments/assets/67a2ad74-254b-4299-8619-601b36144439)

* QA = 100.
* Only QA = a -> 'a' is an even no. greater than '0'.

![image](https://github.com/user-attachments/assets/5f3e1668-596c-48e5-9376-dcf6d72a9f1a)

* QA and DI, VA and LR.

![image](https://github.com/user-attachments/assets/e11388a0-ca59-40c8-bad5-49cb7831a166)
![image](https://github.com/user-attachments/assets/42159367-c84f-4b7d-a2b4-d978697e915d)

* QA total = 100.
* Adding all values in QA -> a + 50 + y + 2a + 2a + 4a + 8a + 2d + 2a -> 19a + 2d + y + 50.
* 19a + 2d + y + 50 = 100.
* 19a + 2d + y = 50.

![image](https://github.com/user-attachments/assets/0fa65b06-1efc-4f11-b795-171ac1438f37)

* a = 2.
* 19 * 2 + 2d + y = 50.
* 2d + y = 12.
* 'd' and 'y' are no. of students and their sum cannot be **negative**, so 'a = 4' is **not possible**.

![image](https://github.com/user-attachments/assets/8786c5b3-4947-4ca0-8423-304e2fcf971f)
![image](https://github.com/user-attachments/assets/2b3273bb-cc3e-470e-84bd-5e84d7bc7fa4)

* Only possibility of 'a = 2'.
* a = 2
* 2a = 4
* 4a = 8.
* 8a = 16.

![image](https://github.com/user-attachments/assets/90e32029-3ce9-4316-bfa0-f36e8c955144)

* 'd and y' value are left.
* a = 2.
* QA -> 19 * 2 + 2d + y + 50 -> 88 + 2d + y.
* VA -> 50 + 2 + 4 + 8 + 4 + d + 4 + 16 + 2y -> 88 + d + 2y.
* QA > VA -> 88 + 2d + y > 88 + d + 2y -> d > y.

![image](https://github.com/user-attachments/assets/69a9ea7f-786e-44b9-abd8-f88346ebfb5b)
![image](https://github.com/user-attachments/assets/93825ed4-e366-4f07-849e-fa220c5b7b35)
![image](https://github.com/user-attachments/assets/deba0486-2868-43b5-8614-6e5b1acca80f)
![image](https://github.com/user-attachments/assets/1057ae8b-d0be-4d89-947f-b6546271c872)

* Pass -> 4 * 2 + 2* 50 + 4 * 4 + 8 + 2 * 16 + y + d + 2d + y + 2y -> 8 + 100 + 16 + 8 + 32 + 3d + 3y -> 164 + 3d + 3y.

![image](https://github.com/user-attachments/assets/9a07e7bb-d25e-4a9d-a8ee-59d9feb689fa)
![image](https://github.com/user-attachments/assets/7b1f6c42-0cbf-433c-9da3-3227e7c54f34)

* We got '2' cases for the value of 'd and y'.
* d = 5, y= 2
* None -> 86 - (3d + 3y) -> 65.
* d = 6, y= 0
* None -> 86 - (3d + 3y) -> 68.
* Min -> 65 [Answer]

![image](https://github.com/user-attachments/assets/1586ee7e-eb29-4779-8b84-24a1d0eeec64)
![image](https://github.com/user-attachments/assets/a0bf5ebc-e1aa-43a9-99b8-817dabd6da94)

* Failed in atmost '1' test -> Failed in '0' tests +  Failed in '1' test -> Passed in '4' tests +  Passed in '3' tests.
* Passed in '4' tests -> 4a -> 8.
* Passed in '3' tests -> 4 * 2a + 4a -> 4 * 4 + 4 * 2 -> 24. [Answer]

![image](https://github.com/user-attachments/assets/8702f25c-ca0d-4e6b-9940-8d5553fc7b7a)
![image](https://github.com/user-attachments/assets/b5552bf0-130f-4c66-b5de-0feb2a583b1d)

* LR and DI -> 2a + 4a + 2a + 50 -> 4 + 8 + 4 + 50 -> 66. [Answer]

![image](https://github.com/user-attachments/assets/194a0b87-474c-4e99-a9ab-0651653d22e0)
![image](https://github.com/user-attachments/assets/99a95d09-4e45-43c5-aa93-056cdd8fdd14)

* QA -> 100.
* QA > VA -> No point in checking 'VA' it cannot have the max. no. of students.
* LR -> y + 3 * 2a + 4a + d + a + 50 -> y + 12 + 8 + d + 2 + 50 -> y + d + 72.
* DI -> 3 * 2a + 4a + d + a + 50 + 16 + 2d + 16 + 2y -> 12 + 8 + d + 2 + 66 + 2d + 16 + 2y -> 2d + 2y + 104.
* DI = 104, QA -> 100, LR -> 72.
* DI > LR -> Always.
* 104 + 2d + 2y > 72 + d + y -> Greater in every aspect whether no. or 'd' or 'y'.

![image](https://github.com/user-attachments/assets/d5cabc60-3345-4803-abc3-7ba02f31a0a5)
![image](https://github.com/user-attachments/assets/5710d497-ac06-4650-89f3-b3f8b88884c5)

* Answer -> DI. [Solution]

#### 2

![image](https://github.com/user-attachments/assets/43b9d201-9b55-45e6-bdc2-03b42ee04370)

* [Question]
* We cannot change '150' on 11th of may.

![image](https://github.com/user-attachments/assets/e24dcee9-d202-4698-b380-9d3d4b38f6de)
![image](https://github.com/user-attachments/assets/d528a1ad-785a-4718-b942-f27249cbcbab)

* Least no. cannot appear on 12th of may.
* Least no. -> Aman
* Max. no. -> Shivam
* Middle no. -> Rohit.

![image](https://github.com/user-attachments/assets/b26a2163-7a47-4496-afce-1e9c1f8ea730)

* Common -> 50.

![image](https://github.com/user-attachments/assets/b69eeda4-af39-4da0-9f14-84851bd0afd5)

* We need to maximize 'a + b + c'
* Max. possible quests -> 152,150,154 OR 154,150,152.
* R -> 152
* A -> 150
* S -> 154
* Min. value -> minimize -> We are taking '0'.

![image](https://github.com/user-attachments/assets/7e2a5c83-6342-4f7f-bfd6-c75b8d3efcdc)
![image](https://github.com/user-attachments/assets/1834b376-1f3f-47f5-8609-c91f3c3c182a)

* Both 'R and S' but not 'A' -> b
* a + b + c = 153
* a + c = 100.
* 100 + b + 153 -> b = 53.

![image](https://github.com/user-attachments/assets/87bebcc7-73da-499e-a4fb-02290d99b556)

* b = 53. [1] [Answer]

![image](https://github.com/user-attachments/assets/8f7f99d4-a020-45ac-b194-0a5957925101)

* We need to minimize 'a + b + c'.
* Maximum/Minimum is not asked in question **2**. We can take anyone of the cases.

![image](https://github.com/user-attachments/assets/a5d38045-3d92-486d-8c4e-898e8c0da0d9)
![image](https://github.com/user-attachments/assets/396e86b9-2392-4f57-be04-68987f8b62b4)

* Max. value -> maximize -> We are taking '0'.
* 146 - 50 -> 96.
* 150 - 50 -> 50.

![image](https://github.com/user-attachments/assets/cc85cc68-e979-4ecf-8718-a1c391bf69a2)
![image](https://github.com/user-attachments/assets/67c7df23-5e75-4253-9662-8d88f5def9ad)

* We don't know the **correct answer** that's why the answer is **Cannot Be Determined(CBD)**. We are getting different/multiple values of 'a' because of many possibilities. [2] [Answer]

![image](https://github.com/user-attachments/assets/7f0e31b7-5a9e-42b8-94bd-6bb4df37bfb9)

* Additional information for Question '3 and 4'.

![image](https://github.com/user-attachments/assets/35ff9fec-16ef-465d-91a4-ac1f47d68ab7)

* Shivam's party -> 11 may -> This happens in case **1** only.
* A -> 146
* S -> 150
* R -> 148

![image](https://github.com/user-attachments/assets/87b61a03-e42a-4e8c-82e7-4786eae4ecdb)

* We need to maximize the value of 'a'.
* Min. is '0'. So 'S' is '0'
* S = 0.
* 2a + 50 = 150 -> a = 50.
* a = 50. [Fixed]
* a + 50 + R = 148 -> R = 148 - 100 -> R = 48.
* R = 48. 
* a + 50 + A = 146 -> A = 146 - 100 -> A = 46.
* A = 46.

![image](https://github.com/user-attachments/assets/a63a791d-91ad-48e0-81ba-2e808e5e9a12)
![image](https://github.com/user-attachments/assets/2acfcfc8-4bbd-41af-af53-b04ff4d766b6)

* Exactly '1' party -> S + R + A -> 0 + 48 +46 -> 94. [3] [Answer] 

![image](https://github.com/user-attachments/assets/f4e3b341-27e7-4b26-ac69-cc94e4c43de7)

* Atleast one of these '3' parties -> Sum of the venn diagram. [Logic] [Concept] [**IMPORTANT**]
* I + II + III -> 274. 

![image](https://github.com/user-attachments/assets/b3d14b00-5cda-4181-a049-8a6b84e7dc5e)
![image](https://github.com/user-attachments/assets/d0ee34bf-30a2-4956-b716-b14727718756)
![image](https://github.com/user-attachments/assets/313fb50e-7c44-40bf-a182-87ce5b24d1db)

* a = 35.
* 98 - a -> 98 - 35 -> 63. [4] [Answer] 

#### 3

![image](https://github.com/user-attachments/assets/65706950-f661-4a18-9eef-79e14801f785)
![image](https://github.com/user-attachments/assets/fb465b20-bb58-4246-8a9b-5b003d7aa7ed)

* [Question]

![image](https://github.com/user-attachments/assets/3967f125-0bc3-4bdf-a790-ded92e38d203)

* Total -> 97.
* M and C -> 30.

![image](https://github.com/user-attachments/assets/84880e4a-0991-4627-9c13-007b25cedbc7)

* y and (30 - y).

![image](https://github.com/user-attachments/assets/42a2a1fd-4247-4438-8133-d15dc4262c4c)
![image](https://github.com/user-attachments/assets/4d3a1f21-7807-431c-94e9-aae90a6628d6)
![image](https://github.com/user-attachments/assets/31270398-60bd-4102-abf4-7479b5277674)

* We have '2' possible casess.

![image](https://github.com/user-attachments/assets/b7ed18a0-3ac3-47b2-8568-a485761ad226)

* M and C.

![image](https://github.com/user-attachments/assets/a4ff2b2c-aa08-48fc-a882-442f5984fcc0)

* Atleast M and C.

![image](https://github.com/user-attachments/assets/2ffa476f-06bf-4579-ab80-c0c5974c2fa0)

* Atleast M and C = M and C -> They are **same/equal** -> It means that only M and only C is '0'.
* a + c = 0.
* a = 0.
* c = 0.

![image](https://github.com/user-attachments/assets/d817786b-0ebf-4d1e-b4f9-216b6ec3a4ec)
![image](https://github.com/user-attachments/assets/051176e5-ebd3-40a1-88b0-3de8b80d408e)
![image](https://github.com/user-attachments/assets/5ddc2265-e1db-4379-b615-5d684af97dd5)

* Case **1**:-
* C -> 47.
* I -> 53.
* M -> 43.

![image](https://github.com/user-attachments/assets/c60507dd-03ee-4eea-b325-5ee66e660c80)

* y = 13.
* 30 - y -> 30 -13 -> 17.

![image](https://github.com/user-attachments/assets/c6f11406-6e4e-4bd4-b179-230dfeba5381)

* x + 30 - x + 30 - 13 -> Should add upto '47' -> 30 + 17 -> 47 -> Satisfying.

![image](https://github.com/user-attachments/assets/ed640651-c452-42ff-b49d-8bf778ce912b)

* Total -> 97.
* People who do not like any of the cuisines or like none of the cuisines -> N. [Let]
* 30 - y + y + x + 30 - x + x - 7 + N = 97 -> 60 + x - 7 + N = 97 -> 53 + x + N = 97 -> N = 44 - x. 

![image](https://github.com/user-attachments/assets/3ef42971-d2ee-4ef8-b0fa-25251648e58a)
![image](https://github.com/user-attachments/assets/be19752e-35ed-4cf4-b994-1faaca9ab39c)
![image](https://github.com/user-attachments/assets/1e18babf-94a7-4605-b9b2-4596134a10a0)

* Like M and I but not C -> y -> 13.
* (x - 7) -> Can be '0' or can be a positive no. but cannot be negative. So 'x' should be 'x >= 7'.
* (30 - x) -> Can be '0' or can be a positive no. but cannot be negative. So 'x' should not exceed '30' i.e 'x <= 30'.
* Range of 'x' -> 7 <= x <= 30.

![image](https://github.com/user-attachments/assets/856eb13e-e9e0-45a0-8bcd-2832c848578a)
![image](https://github.com/user-attachments/assets/d8042625-613f-4c10-92dd-2830dfdd14cd)

* As we want the min. value of 'N', so we will take the largest value of 'x' which is '30'.
* x = 30.
* N = 44 -x -> 44 - 30 -> 14.

![image](https://github.com/user-attachments/assets/70e31602-98b0-4011-8799-4eb1f8b1f32b)

* N = 14.
* People like all of the cuisines -> 30 - x.
* As we want the max. value, so we will take the smallest/minimum value of 'x' which is '7'.

![image](https://github.com/user-attachments/assets/9360d234-ceb0-4f64-9b46-b81785117fff)
![image](https://github.com/user-attachments/assets/c73657b4-0932-455a-aac9-eb22cce56abd)

* 30 - x -> 30 - 7 -> 23. [Answer]

![image](https://github.com/user-attachments/assets/5f0d273b-77df-4ab5-b942-e346364c6bc5)

* Case **2**:-
* C -> 53.
* I -> 59.
* M -> 47.

![image](https://github.com/user-attachments/assets/f53699e2-53cc-48d2-9253-f4fc0acc2121)
![image](https://github.com/user-attachments/assets/9d0e1e6f-002f-4860-a0bb-775a2a176323)

* y = 17.
* 30 - y -> 30 -17 -> 13.
* x + 30 - x + 30 - y(17) -> Should add upto '53' -> 30 + 13 -> 43 -> Not Satisfying.
* We need '10' more but only C is '0'.

![image](https://github.com/user-attachments/assets/f05046bb-dfaa-4823-a36b-fe13b4cb454a)
![image](https://github.com/user-attachments/assets/b0f0e8fc-a9bb-477b-bdea-2081b8a1f7fa)

* This is **not possible**.

#### 4

![image](https://github.com/user-attachments/assets/a0dd62c9-ec56-4dc9-82cf-91aefa75dcac)

* No one playing all of the '3' games -> III -> 0.
* Everyone is playing atleast '1' of the '3' games.
* Exactly '1' game(I) + Exactly '2' games(II) + Exactly '3' games(III) -> 300.
* I + 2 * II + 3 * III -> 210 + 170 + 220 -> 600.

![image](https://github.com/user-attachments/assets/76f5dffa-3c72-48d2-b80e-02fee6bf2b7e)

* III = 0.

![image](https://github.com/user-attachments/assets/b98891b4-8426-4c74-8ada-5c1cb54c4a36)

* Exactly '2' games(II) -> 300
* Total -> I + II + III -> 300.
* I = 0, II = 300, III = 0.

![image](https://github.com/user-attachments/assets/6204146e-e2d0-40ca-996a-59ca21b3f325)
![image](https://github.com/user-attachments/assets/cf855bf5-0031-48d9-8cc5-fa19fca8eae6)
![image](https://github.com/user-attachments/assets/143b6e02-3a35-4010-a744-10abee5bdbf9)

* Nobody is playing all '3' sports, it automatically means that nobody will be drinking all of the '3' drinks. [Logic]

![image](https://github.com/user-attachments/assets/b0480763-e5b2-49aa-8d1b-a9bbf452dd8c)

* Intersection part.

![image](https://github.com/user-attachments/assets/4fe6b8a1-f9d2-4736-abb6-66fbb10a2166)

* Exactly '2' -> 300.
* Football -> 220.
* Cricket and hockey both -> 300 - (220 + 0 + 0) -> 80.
* Hockey -> 170.
* Cricket and football both -> 300 - (170 + 0 + 0) -> 130.
* Cricket -> 210.
* Football and hockey both -> 300 - (210 + 0 + 0) -> 90.

![image](https://github.com/user-attachments/assets/0071aefb-f13c-401c-93ca-03b2bff6ccc6)
![image](https://github.com/user-attachments/assets/788c3ec4-0e23-4d16-a775-b6d8114d2237)

* Only '80' people play **Cricket and hockey both**. So max. '80' people can drink **Pepsi and sprite** both.
* Max. value -> 80. [Answer] [1]
* **Drink sprite** can be interchanged with **playing hockey**.
![image](https://github.com/user-attachments/assets/95d9bcd8-1ddf-409c-970f-436347cb60c5)

*  Cricket and hockey both -> 80. [Answer] [2]
* **Drink sprite** -> Play hockey.
* **Drink pepsi** -> Play cricket.
* **Drink frooti** -> Play football.
* Play hockey and Play cricket and Play football -> III -> 0. [Answer] [3]

![image](https://github.com/user-attachments/assets/87c67e9d-f2d2-4dca-b464-3e1452af1b4f)
![image](https://github.com/user-attachments/assets/6a45a544-0f53-4f44-b521-a90c205d8e97)

* Red part -> maximize.
* 'F and H' -> maximize -> 90.
* Total -> 140.
* Drink sprite but do not play football -> 140 - 90 -> 50 -> minimize.
* minimize -> 50. [Answer] [4]

#### 5

![image](https://github.com/user-attachments/assets/e2e2c63a-0f82-41a1-9b96-b37817c9a69d)
![image](https://github.com/user-attachments/assets/2cfed9b8-aa68-4741-9eed-0d66c8a1e180)

* [Question]
* 4-parameter venn-diagram.

![image](https://github.com/user-attachments/assets/c8cf42b7-f413-495e-a160-a7c9c93b2e5c)
![image](https://github.com/user-attachments/assets/3707b592-1fa0-4625-b6d3-1fdda6c4d903)

* As they are taught at the same time so no students have enrolled which means those parts are '0'.
* DM = 30.
* These '30' people are enrolled in exactly '3' courses.

![image](https://github.com/user-attachments/assets/c69854bb-7294-4cc6-b2b4-7356e44774d0)
![image](https://github.com/user-attachments/assets/adcce345-8c27-42fa-b466-2fae58075902)
![image](https://github.com/user-attachments/assets/b6425390-89e5-410e-9f79-c561f0d87c62)

* The rest will be '0'. 'DM = 30' and the total is also '30', so the rest is '0'.
* None = 0.
* We are making diagram for enrolled. So the total of the diagram is '220'.

![image](https://github.com/user-attachments/assets/152e42f5-4177-4f5c-a617-17a262132871)
![image](https://github.com/user-attachments/assets/b670a95a-093b-4aef-a85a-146ba5d9b7d3)

* Exactly '2' courses -> d + e + f + 0 + 0 + 0 = 100.
* Exactly '2' courses -> d + e + f = 100.
* Exactly '1' course -> 3 * a -> 3a.
* 3a < 30 -> a < 10.

![image](https://github.com/user-attachments/assets/8d6b3668-eed7-4269-93d4-21f3a552d913)

* Exactly '3' courses -> b + 0 + 0 + 30 -> b + 30.
* Exactly '3' courses -> b + 30.

![image](https://github.com/user-attachments/assets/4fc07ea3-b930-4d07-baec-2af4ac7a80dd)

* Exactly '3' courses < 100 -> b + 30 < 100.
* Exactly '3' courses be '99'. [Let]
* Exactly '2' courses -> 100 -> Fixed.

![image](https://github.com/user-attachments/assets/04175394-a06b-4695-b831-5dc1bf1c63a2)

* Exactly '1' courses -> 3a -> Always greater than 20 -> 3a > 20.
* 3a > 20 and 3a < 30 -> 21, 24, 27 -> Multiples of '3'.

![image](https://github.com/user-attachments/assets/95095a5b-efd2-4730-88aa-1219f6c374b4)

* Not in QA(QA`) -> Outside of QA -> 2 * a + f + 30 -> 2a + f + 30.
* Not in LR(LR`) -> Outside of LR -> 2a + e.
* Not in GK(GK`) -> Outside of GK -> 2a + d.
* QA` : LR` : GK` -> 4 : 3 : 1 -> 4x : 3x : x.

![image](https://github.com/user-attachments/assets/5e6793a9-e5e8-478c-8230-e7ddac2ae0e6)
![image](https://github.com/user-attachments/assets/67121dd3-9352-4e6e-b0bf-458cfb55ce13)

* Adding all of the '3' equations into '1'.
* d + e + f = 100.

![image](https://github.com/user-attachments/assets/2953cabd-afd9-4f06-8ce5-ba2627313b8e)
![image](https://github.com/user-attachments/assets/daeba08a-a497-4d7d-8811-55cddae1002e)

* Dividing by '2' on both the sides.
* We got '3' values of '3a' and see which value satisfies the above **equation**.

![image](https://github.com/user-attachments/assets/905f7f6d-0142-4998-a8e6-5e39f0318a8d)

* 3a = 21 -> 'x' will not be an **integer** -> not possible.
* 3a = 24 -> 'x' will not be an **integer** -> not possible.
* 3a = 27 -> 'x' isa an **integer** -> possible.

![image](https://github.com/user-attachments/assets/10f9c9be-c8ca-481a-9bb0-e80b34b1a33e)
![image](https://github.com/user-attachments/assets/64e83d0b-9242-48d1-aaa0-5339242d9eb3)

* x = 23.
* 3a = 4x - 65 -> 3a = 92 - 65 -> 3a = 27 -> a = 9.
* a = 9.

![image](https://github.com/user-attachments/assets/9936529a-fec0-48c5-b64f-24ed5b6378c5)
![image](https://github.com/user-attachments/assets/6e4e95db-d92b-4de5-8bd5-8040643d3944)
![image](https://github.com/user-attachments/assets/ee025dfb-df56-4b9f-b257-d25882ded27f)

* 2a + d = x -> 18 + d = 23 -> d = 5
* d = 5.

![image](https://github.com/user-attachments/assets/bbd3beec-89a8-43a9-8dc2-199765a2a0b4)

* 2a + e = 3x -> e = 69 - 18 -> e = 51.
* e = 51.
* 2a + f + 30 = 4x -> f = 92 - 30 - 18 -> f = 44.

![image](https://github.com/user-attachments/assets/0084f751-42dc-451a-becf-0bef441a5c75)
![image](https://github.com/user-attachments/assets/e4ba1117-ac96-40bd-8dfa-5b2decd00392)

* Only 'b' left.
* Total sum -> 220.
* b = 220 - (9 + 5 + 9 + 51 + 44 + 0 + 0 + 30 + 0 + 0 + 0 + 9 + 0 + 0) -> b = 220 - 157 -> b =  63.
* b =  63.

![image](https://github.com/user-attachments/assets/3029a091-9a4c-4a5b-b22b-aeb6afc0193f)

* GK -> 197 [Answer] [1]

![image](https://github.com/user-attachments/assets/06b49561-a7dc-496e-b922-810889f4af2e)
![image](https://github.com/user-attachments/assets/a6ae9924-c8d6-4d0d-aaa7-c902afe6166d)
![image](https://github.com/user-attachments/assets/e4099e68-a3db-4e1a-a7d6-f7bf7a99b6a9)

* Exactly '1' stream -> 3a + 0 -> 3 * 9 -> 27. [Answer] [2] 
* QA and LR -> 68. [Answer] [3]
* QA` = 4x = 92. [Answer] [4]

#### 6

![image](https://github.com/user-attachments/assets/e07b27fc-ea84-4cad-8fed-6543903bfab1)

* [Question]
* 62.5% -> 5/8.

![image](https://github.com/user-attachments/assets/1bcdfdae-bee5-442a-98c4-57a6c16aac1f)
![image](https://github.com/user-attachments/assets/61e1d0b1-0e1e-4c0e-85dc-a098b76bc5ed)

* All values are distinct.

![image](https://github.com/user-attachments/assets/5e091674-db09-4c90-acca-9b8184219ed1)

* 0.8 * 40000 -> 32000.

![image](https://github.com/user-attachments/assets/cc4817a5-2cc9-4d43-8f82-089e5f8b3244)

* 'x' cannot be '40000'.
* x = 30000
* 0.8 * 30000 -> 24000.

![image](https://github.com/user-attachments/assets/cdca9972-8f4e-45bb-87a2-70c2452b0a2c)

* Sum of '4' nos. is '24000' -> 4K + 5K + 7K + 8K -> 24K.

![image](https://github.com/user-attachments/assets/ea6be49e-62db-445a-a1ba-2edeb4ad533a)
![image](https://github.com/user-attachments/assets/f25bd52e-14b5-4ea9-9fde-b1c7d3724e32)
![image](https://github.com/user-attachments/assets/6f96d23d-5ad1-4ea3-92d5-eeccd823cb7d)

* If 'e = 3000'.

![image](https://github.com/user-attachments/assets/9ecba3e5-d595-4497-9639-4d79d5cdd0e3)
![image](https://github.com/user-attachments/assets/efe33ce2-f0b7-4f1d-8f6d-35d361a40110)

* l = 4000.

![image](https://github.com/user-attachments/assets/3c27c7f0-516b-45e2-ab47-cb340837b04b)

* h = 12000 - 1K - 2K - 4K -> h = 12000 - 7K
* h =  5000.

![image](https://github.com/user-attachments/assets/0fe83472-1ac8-4e6e-8f86-5d1382103eea)
![image](https://github.com/user-attachments/assets/efae2905-1604-4dc3-afcd-e5627c3eecb8)
![image](https://github.com/user-attachments/assets/ed24f9ee-728a-4471-9c42-ebe24d374c5f)
![image](https://github.com/user-attachments/assets/cddd5fbe-79d1-4f17-b544-279c50fbb7c8)
![image](https://github.com/user-attachments/assets/475a1063-07ba-4156-a53b-17445a67a104)

* i = 9000 -> not possible.

![image](https://github.com/user-attachments/assets/90904d07-35ff-446f-b1a5-c1e14009b126)
![image](https://github.com/user-attachments/assets/4c39d49e-cc34-441c-aa77-ef8e03c04fea)

* i = 8000 -> possible -> They are adding upto '30K'. [Answer] [1]

![image](https://github.com/user-attachments/assets/79401646-b901-4595-8e51-ed30e6bf486d)
![image](https://github.com/user-attachments/assets/4b0e2682-70f2-4dd5-9fe2-6aea72707855)

* 10 combinations -> Circled in red. [Answer] [2]

* Min. possible value of 'm' is '7000'.

![image](https://github.com/user-attachments/assets/658fdb02-fe71-4cdc-a398-88f782437caa)
![image](https://github.com/user-attachments/assets/2796fa1b-d694-47d4-a1af-bb58237ac0a2)
![image](https://github.com/user-attachments/assets/40dd884e-2967-45bf-91e5-59751ba45256)

* h + e + j + m -> 5 + 2 + 0 + 7 -> 14000. [Answer] [3]

![image](https://github.com/user-attachments/assets/7ad8ce21-1d67-47fd-b9b8-b7c0e00f815d)
![image](https://github.com/user-attachments/assets/314c1432-9feb-40d2-9307-f2a20b6e7601)

* Stat A -> False.
* Stat B -> False.
* Stat C -> True.
* Answer -> 1. [Answer] [4]

![image](https://github.com/user-attachments/assets/a2cf8cb5-ecd8-4067-8825-ceb523cf96ab)

* 2000 -> c,d,e,o -> 4.
* 2000 -> c,d,e,o,g -> 5.
* Exactly 4 or 5.

#### 8 

![image](https://github.com/user-attachments/assets/4953b42c-a43c-41b8-ac96-a162b6e732c2)

* [Question]

![image](https://github.com/user-attachments/assets/355b790b-c5f8-4615-90d6-4654255bccb5)
![image](https://github.com/user-attachments/assets/434fc9d6-7cc0-4526-9286-e1f94d5af10b)

* Can speak only '1' language -> 2x + 3x + 4x -> 9x.
* Can speak exactly '2' languages -> a + b + c.

![image](https://github.com/user-attachments/assets/481f79a5-b67e-4ade-8f8d-e5e50ed6ee0f)
![image](https://github.com/user-attachments/assets/e63b87e1-3881-43f6-978e-b1cd3a6dde64)

* No. of people who can speak English -> a + c.
* No. of people who can speak Spanish -> a + b.
* No. of people who can speak French -> c + b.

![image](https://github.com/user-attachments/assets/0a04a976-d4bf-428a-8774-263613665cea)

* a+c/b+c = 2/2 -> a+c = b+c -> a = b.

![image](https://github.com/user-attachments/assets/f0b1d25d-899b-4d3d-b469-8a9f35d16ee4)

* a = b -> b = a.
* c = 3b -> c = 3a.

![image](https://github.com/user-attachments/assets/bed9cea5-bcb3-4185-ab1f-a3b077b5c74d)
![image](https://github.com/user-attachments/assets/f27a4690-ceb0-4356-b131-753b84ae3ac3)

* k = 2.5a

![image](https://github.com/user-attachments/assets/5f4cad07-73f5-4924-900d-fb8bbf4564cd)

* French.

![image](https://github.com/user-attachments/assets/0ee116a0-d2dc-408d-bcc5-df7be004030c)

* English
* Total people -> 250.

![image](https://github.com/user-attachments/assets/89a6282d-20a3-43ba-b3dd-e0e3ef287562)
![image](https://github.com/user-attachments/assets/bc58489f-bde4-4011-bedd-206750c4ae17)

* [Formula] [**VERY IMPORTANT**] [Concept]

![image](https://github.com/user-attachments/assets/ec06215f-ca56-4cbf-92fd-3bfd85f740a4)
![image](https://github.com/user-attachments/assets/c8991725-a5e2-4d2a-88e6-d77705768884)
![image](https://github.com/user-attachments/assets/3711afc9-c15f-44aa-8c3c-0e1a6a45379d)

* k = 2.5a -> We want '2.5a' to be an integer.
* 'a' cannot be **odd**.

![image](https://github.com/user-attachments/assets/8b4b8836-46e0-4168-8bbc-aa8a60161050)

* 'x' cannot be '0' otherwise all of the '2x,3x and x' will be '0' and the ratios will not fit in properly.
* a < 5x.
* If 'x = 0' then 'a < 0' and 'a' cannot be negative. 

![image](https://github.com/user-attachments/assets/ebf71e6c-94db-459f-b6d3-50fd8b26d784)

* We have '2' cases fo 'x and a'.

![image](https://github.com/user-attachments/assets/d54a3fc2-e2a3-49ad-b20a-3ed4ef0a5ee5)
![image](https://github.com/user-attachments/assets/4a042660-623c-47de-aadd-bd4858666a19)

* If 'x =10' then 'a = 28'
* a < 8x/3 -> a < 80/3 -> a < 26.67 -> 28 < 26.67 ->  not satisfied.

![image](https://github.com/user-attachments/assets/b384a2b9-50fc-4e54-ab15-0136fbb32bb5)

* x = 20, a = 10 -> satisfied.
* a < 8x/3 -> a < 160/3 -> a < 53.33 -> 10 < 53.33

![image](https://github.com/user-attachments/assets/0c09ab12-92c5-4926-a140-0ff310b7cdf9)

* y = mx + c. [Formula] [**VERY IMPORTANT**] [Concept]
* Slope -> coefficient of 'x'.

![image](https://github.com/user-attachments/assets/b8399a45-1c6e-43a7-b0a8-7ca37e9ab7be)

* x = 20, a = 10
* 2x = 40.
* k = 2.5a -> 25.

![image](https://github.com/user-attachments/assets/82f37928-143a-446c-80a4-9c1cb54f9b6a)

* Only English -> 2x -> 40. [1] [Answer]
* Do not speak spanish -> 2x + 3a + 4x -> 150.
* Learn Eng and Spa -> 3x -> 60.
* Out of the '150' people who do not speak spanish, '60' people learning Eng and Spa. So, '150 - 60 -> 90' people can learn spanish. [2] [Answer]

![image](https://github.com/user-attachments/assets/5352b8e5-3918-406f-806f-aa720630a4c1)
![image](https://github.com/user-attachments/assets/988eb263-8e99-4c83-a5b1-f62cd7eb1b5c)

* Only French -> 20. [3] [Answer] 
* Max. people who speak French -> 30 + 20 + 10 + 80 -> 140.
* Out of the '140' people '30 + 20 -> 50' people already speak english. So, '140 - 50 -> 90' people want to learn english who already know french.
* 90 -> Know French and want to learn Eng.
* Learn Eng -> 25.
* Learn Eng and Spa -> 60 -> These(60) people come from the '80' people who speak french only.
* Only know French -> 80 - 60 -> 20.
* Speak Eng and Spa -> 10.
* 20 + 10 -> 30 -> Out of these '30' people '25' want to learn english.
* 30 - 25 -> 5.
* 90 - 5 -> 85 -> maximum. [4] [Answer]

![image](https://github.com/user-attachments/assets/0da85eaa-f6a3-418d-8fd4-bf4e7ae5b920)
![image](https://github.com/user-attachments/assets/e3754132-e553-47cb-a30a-13b4722bd52e)
![image](https://github.com/user-attachments/assets/9e66e957-5170-4ef3-82ea-3bdce94d41f0)

* Do not speak Eng or French -> Outside of Eng and French circles -> Speak only Spanish -> 60.
* Max. possible value -> 60. [5] [Answer]

#### 9

![image](https://github.com/user-attachments/assets/bb8cd3c5-9d8f-4b5f-b070-a93893491663)

* [Question]
* G and S but not M -> d 
* M and G but not S -> e 
* G and S and M -> g
* Only S -> b
* M and S but not G -> f

![image](https://github.com/user-attachments/assets/842418e0-d690-457b-bbdb-a073c6e2fdd5)

* both M and G -> e + g.
* both S and G -> d + g.

![image](https://github.com/user-attachments/assets/45c65cb6-190b-4a2a-a0d5-98f76ede4b91)
![image](https://github.com/user-attachments/assets/d09975e2-8b34-4ded-8903-092cf1ebb269)

* e = g + 2d -> e > g + 2d -> e > 2d.

![image](https://github.com/user-attachments/assets/3d21adec-8df2-4de3-ad76-97dddd2706a8)

* f = 5 + d.

![image](https://github.com/user-attachments/assets/b7ec2b31-4a46-4104-b138-0e28ffbf424d)

* d = d.
* g = 2d
* e = 4d.

![image](https://github.com/user-attachments/assets/1dec3fdc-09d2-4154-817b-1db594fed25e)

* Total -> 115.

![image](https://github.com/user-attachments/assets/656ec15c-8bd1-4c32-8b39-e0d7bb618c45)

* RHS -> Multiple of '10'.
* LHS -> Should be a multiple of '10' as equal to(=) in-between.
* d -> already in multiple of '10'
* a + c -> need to be in multiple of '10'.

![image](https://github.com/user-attachments/assets/a991c8cd-0cce-4532-9e3c-754c37965571)

* 6 <= a,c <= 12.
* a + c = 20.
* We have many combinations of 'a and c' adding to '20'. 

![image](https://github.com/user-attachments/assets/088d549e-ddb4-451e-8682-fe97ca0f2278)

* d = 8.
* b = 10 + 2d -> 26.
* b = 26.

![image](https://github.com/user-attachments/assets/5d88a914-e936-4dec-bb61-26ba3337e6dd)
![image](https://github.com/user-attachments/assets/415b7fb5-2a22-4213-843c-b0b236b2b507)

* We need to find 'a and c'.

![image](https://github.com/user-attachments/assets/a47caf03-cbed-417e-a010-90891676a2d9)
![image](https://github.com/user-attachments/assets/f02d6b39-e439-4d38-ad9a-38724db0fbc4)

* Both G and S -> d + 2d -> 24. [1] [Answer]

![image](https://github.com/user-attachments/assets/9a94826f-1f2a-46a6-af0f-e92753c50ef8)
![image](https://github.com/user-attachments/assets/eb971ba8-4b48-4b39-a822-0b6dc4dab6dd)

* Out of the '5' groups, in '3' groups we have repeatation of '2' values.
* 3/5 -> 0.6 -> 60%. [2] [Answer]

![image](https://github.com/user-attachments/assets/645072cb-c902-4e7c-928b-2037cab75504)

* Voted for all '3' venues -> g -> 2d -> 16.
* Only S and M -> f -> 5 + d -> 13.
* 16 - 13 -> 3.  [3] [Answer]

![image](https://github.com/user-attachments/assets/f48f39d6-f7d3-42cc-9f5f-194c5b4fb38d)
![image](https://github.com/user-attachments/assets/19d56cf1-fb24-4069-8dc2-37ec4b523043)

* For min. we have to take min. value of 'a'. [4] [Answer]

![image](https://github.com/user-attachments/assets/02bd2fc5-3813-43c8-a2f6-b2e53466b7fc)

* Only G and M -> a + c -> 20. [5] [Answer]

#### 10

![image](https://github.com/user-attachments/assets/60abb480-79e7-49f4-bf91-8ecdbb084abd)
![image](https://github.com/user-attachments/assets/efc55ddc-92e1-413d-a837-310120359b6b)
![image](https://github.com/user-attachments/assets/e323e9a5-fdee-439b-99f6-01b49dddb02f)

* [Question]
* Total -> 250

![image](https://github.com/user-attachments/assets/6ce95444-04ca-44a1-bc11-2e2d1f7786bd)

* a + 15 - a + 20 + 30 -> 65.

![image](https://github.com/user-attachments/assets/f8d0d658-2f16-452a-99aa-e3c635e8e3fe)

* Exactly '3' projects -> 30% of 250 -> 75.
* c + 50 - c + 10 + 15 -> 75

![image](https://github.com/user-attachments/assets/7237f11f-057d-4ab8-aa16-fa6be62b2749)

* k = 40% less -> 2/5 less -> 1 - 2/5 -> 3/5.
* k * 3/5 = 15 -> k = 25.
* Exclusively on 'A,C and D' -> c.
* 50% of c -> c/2. 

![image](https://github.com/user-attachments/assets/f1e7e538-bf9b-4c56-ae39-559ea4665c84)
![image](https://github.com/user-attachments/assets/5870f19e-6aa3-44a9-b0dd-e381a8e6cc49)
![image](https://github.com/user-attachments/assets/00005410-8bf8-4663-be59-fe7d1f9dc581)
![image](https://github.com/user-attachments/assets/47e08aad-ce62-4f18-81bd-7c0c9e44d961)
![image](https://github.com/user-attachments/assets/17bc6a30-6dee-4038-8d1e-067bdfdf56c4)
![image](https://github.com/user-attachments/assets/25d8145b-7c32-4bd8-938d-08d78f8571e3)
![image](https://github.com/user-attachments/assets/24b609fd-dffa-434d-a613-8e6ec024e5d9)
![image](https://github.com/user-attachments/assets/e9fe5e4b-3411-4a5f-ba4c-140bc1634d60)
![image](https://github.com/user-attachments/assets/01122620-2070-4cd9-874b-db4bafc65433)

* A and C -> 15
* C and D -> 10
* Diff -> 15 - 10 -> 5.

![image](https://github.com/user-attachments/assets/c028736e-a202-4a83-a4c7-36dc565a9fb5)

* Not A and Not D -> 30 + 25 + 10 -> 65. [I]
* Not B and Not D -> 5 + 15 + 10 -> 30. [II]
* Exclusively on '2' projects -> 10 + 15 + 15 + 25 + 15 + 10 -> 90.
* Atleast '3' projects -> Exclusively on '3' projects + Exclusively on '4' projects  -> (15 + 20 + 10 + 30) + 20 -> 95.

![image](https://github.com/user-attachments/assets/bbc884d9-db14-4314-8551-f72f994f1835)
![image](https://github.com/user-attachments/assets/c2890850-0753-4507-b3df-b8a548afe461)
![image](https://github.com/user-attachments/assets/d7b3e0aa-37e1-4b66-8077-4dd2e428919f)

* Worked on D -> 20 * 3 + 2 * 10 + 2 * 15 + 30 -> 140.

![image](https://github.com/user-attachments/assets/41f4bf84-0f9a-451f-b6cc-abecdbdd72de)
![image](https://github.com/user-attachments/assets/1d4dc1c5-10e8-4077-9698-e286e78ac8d2)

* Worked on B -> 20 + 2 * 10 + 2 * 15 + 30 * 2 + 25 -> 155.

![image](https://github.com/user-attachments/assets/77a3ef6e-3281-428d-a7d2-88ee63d92744)

* Exclusively on 'C' -> 10.
* Exclusively on 'B,C,D' -> 30.
* a = 1, b = 3
* a * b -> 1 * 3 -> 3.

### Mixed Practice (7)

![image](https://github.com/user-attachments/assets/62de488d-1a3d-47ae-a4f5-5547949b6b92)
![image](https://github.com/user-attachments/assets/2b2412c9-f06a-4a6a-b793-12d6eea23ee7)
![image](https://github.com/user-attachments/assets/348bbba1-937f-485c-a205-b28a9f568044)
![image](https://github.com/user-attachments/assets/434f3f5d-c8d1-42cc-b38a-f8200184cb34)

* [Question]
* 4-parameter venn diagram.
* Atleast '3' dishes -> III + IV -> 50.
* Atleast '2' dishes -> II + III + IV -> 182.
* Atleast '1' dishes -> I + II + III + IV -> 295.
* Both CB and MB -> B,L,P,H -> 0.
* Both CB and DF -> K + L + J + P -> K + J. [J = 0, P = 0] 
* Both MB and DF -> L + M + P + N -> M + N. [L = 0, P = 0] 

![image](https://github.com/user-attachments/assets/fe1c3d80-f61d-43af-92a8-0bb0573f4647)

* 'PK' is not ordered without 'DF'.
* 'PK' without DF -> all of them -> '0'.

![image](https://github.com/user-attachments/assets/b11ef523-f5e4-4005-8088-bdf6cf58ddf8)
![image](https://github.com/user-attachments/assets/71e3cd3b-03e8-496b-b0cf-0359ba0af697)

* IV = 0.
* III = 50.
* L + J + H + N -> III -> 50. [L = 0, H = 0]
* J + N = 50. 

![image](https://github.com/user-attachments/assets/e4e1ff15-2c23-453d-9b53-2e21c6d922bb)

* II + III -> 182. [III = 50]
* II = 132.
* B + K + M + I + G + E -> II = 132.
* K + M + E = 132. 

![image](https://github.com/user-attachments/assets/979dc532-240d-45a9-8359-e76c2091d370)
![image](https://github.com/user-attachments/assets/c5a09fe4-acdc-40b6-94b2-edfb3d8bf9e0)
![image](https://github.com/user-attachments/assets/88c005a7-dca2-4050-ad96-64b270da292d)

* I = 113.
* A + C + D = 113.
* C + M + N -> Total no. of people who ordered MB.

![image](https://github.com/user-attachments/assets/ac386afd-ca5a-4122-9868-c7f61c1b2dbd)

* Weighted Average. [**IMPORTANT**] [Formula] [Concept]
* C * 1 -> 'C' people ordered '1' dish.
* M * 2 -> 'M' people ordered '2' dishs.
* N * 3 -> 'N' people ordered '3' dishs.
* C * 1 + M * 2 + N * 3 -> Total no. of MB dish ordered.

![image](https://github.com/user-attachments/assets/29a079fc-c0e3-48e7-b03d-9c0e25b37e97)
![image](https://github.com/user-attachments/assets/841de6c8-8375-4970-82df-f4afed424b8f)

* We have do **cross-multiplication**.

![image](https://github.com/user-attachments/assets/b03c62f6-8f2a-4e9c-bad0-2059bae6737d)
![image](https://github.com/user-attachments/assets/3cb4d9f8-4c89-427c-9f92-79d6e8d8c419)
![image](https://github.com/user-attachments/assets/15c42054-fe8f-480a-9af1-63f10b82adac)
![image](https://github.com/user-attachments/assets/79230faa-7159-4b4a-8ce7-11fa09a1f6a8)
![image](https://github.com/user-attachments/assets/cf62b5e3-30e4-447f-89a5-e41a21e31a10)

* D = E.
* J + N = 50.
* D = E = 50.

![image](https://github.com/user-attachments/assets/43beb7b6-feb9-4694-802d-36a5fa83009c)
![image](https://github.com/user-attachments/assets/3e1b4587-52dc-49fc-9402-a957d477cdd6)
![image](https://github.com/user-attachments/assets/47de6cc8-aae8-49c6-a60d-485e1dcbcc71)
![image](https://github.com/user-attachments/assets/4625ad0c-3063-4467-9a36-503c19cdf24e)

* Total Venn Diagram -> 295.
* Left -> 295 - D - E -> 295 - 50 - 50 -> 195.
* A + C + K + M + J + N -> 195.

![image](https://github.com/user-attachments/assets/6c0fc698-cd9e-4388-ae07-de11d62b2869)

* A + C -> 63.
* K + J -> 48 + M + N.

![image](https://github.com/user-attachments/assets/0a6af71d-fa94-4017-a5a2-0c72aac7efa1)
![image](https://github.com/user-attachments/assets/171a3921-4fb7-404b-8c0f-bef3087a9bf2)

* C = N + 13.

![image](https://github.com/user-attachments/assets/c59cf0fc-1151-467f-b058-54c0fa662303)
![image](https://github.com/user-attachments/assets/4e6de099-1bc8-4bfc-9a91-a8176176e950)
![image](https://github.com/user-attachments/assets/8f5a68c4-bb5b-4fff-abc4-399665255f14)

* N = 10
* C = N + 13
* C = 23.
* A + C = 63.
* A = 40.
* J = 40.
* K + A = 90
* K = 50.

![image](https://github.com/user-attachments/assets/de4e124f-5295-43a1-8448-0b2ed8cd2242)
![image](https://github.com/user-attachments/assets/2bd9ab14-5c85-44d9-9956-2ef6526ddc8d)
![image](https://github.com/user-attachments/assets/e769bad3-f328-4675-9caf-085dae7ebdd8)
![image](https://github.com/user-attachments/assets/2c2c39b4-6c9a-4e9c-bf40-f5f3e1a2ec7e)

* [Question]
* max. -> be careful. [**IMPORTANT**] [Logic] [Concept]
* Total -> 100 people. [Let]
* Max. -> 10%.
* 1/3 of 100 -> 66.67
* We have to take '4' steps so that we can reach '1/3' faster. We cannot do so in less than '4' days.

![image](https://github.com/user-attachments/assets/5aa8c46d-6aaf-413d-84c3-662fab081a89)
![image](https://github.com/user-attachments/assets/fe4dfdcb-7920-473c-aadb-4ce70e47fc8d)

* Max. we can keep same is  'F, S, Su, M'.
* According to the question, the '1/3' reduction is applicable to the mondays of the month of april only. [Logic] [**IMPORTANT**] [Concept]

![image](https://github.com/user-attachments/assets/1c4cdaac-38ba-42ae-b7da-0a49cdebf253)
![image](https://github.com/user-attachments/assets/e6e748f5-9ff5-4691-b0a4-83bacd987a7a)
![image](https://github.com/user-attachments/assets/ef6540e9-90cd-4eba-ac46-ccfbe159b3de)

* 25th April -> Last Monday of april
* 2nd May -> Next Monday.
* We are in may now and the '1/3' reduction worked in april only.
* 4th Apr to 11th Apr -> 4days.
* 11th Apr to 18th Apr -> 4days.
* 22th Apr to 30th Apr -> 9days. [1] [Answer] [**VERY IMPORTANT**]
* 9 > 4. 

![image](https://github.com/user-attachments/assets/96637037-8c6f-46d8-80f3-82d8f29e185f)
![image](https://github.com/user-attachments/assets/a23b5c8f-1fbf-4e07-be44-aee4638cc6d1)

* We have to maximize on '1st of april' because after that everytime the no. of workers are getting reduced. [Logic] [**IMPORTANT**] [Concept]

![image](https://github.com/user-attachments/assets/ce031eab-e69a-47da-b135-3de9ec90108d)
![image](https://github.com/user-attachments/assets/2e6546ee-de61-47f7-8bc8-aee7362cb7a9)

* [Formula] [**IMPORTANT**] [Concept]

![image](https://github.com/user-attachments/assets/e8a22628-44ef-48fe-819d-5cf7c14b329d)
![image](https://github.com/user-attachments/assets/50d3f7c8-fceb-4344-9f40-7e83d1ae7b19)

* 55 to 49 -> 11% decrease.
* Max. is 10%. So we cannot take '55', we will take '54'.

![image](https://github.com/user-attachments/assets/7b23e66c-2afc-4665-a40d-09c80d98fdb3)

* Jump from 11th april to 4th april.
* 10% decrease -> 1/10 = n/n+d -> n = 1, d=9.
* n/d = 1/9 increase.
* We we go from 1st to 2nd april -> 10% decrease.
* We we go from 2nd to 1st april -> 1/9 increase.

![image](https://github.com/user-attachments/assets/96309c92-886a-4b41-9fe0-6135d3b77547)
![image](https://github.com/user-attachments/assets/2548b1e5-8657-45cb-aa68-89511b180012)

* Max -> 111. [Answer] [2] [**VERY IMPORTANT**] 

![image](https://github.com/user-attachments/assets/1db28fb0-a90b-4aa5-a15b-ebd8ab27ac54)
![image](https://github.com/user-attachments/assets/24587626-8c4b-41e5-b780-3d6a6c8dbe72)

* We have to maximize.
* The women work force is **increasing** as the months goes on. So we can maximize on 30th april.
* It is opposite to men as men work force is **decreasing** as the months goes on. So we can maximize men on 1st of april.
* Max. increase is '10%'.
* 4th april -> x. [Let]
* 11th april -> 1.5x -> 26.
* 'x' will not be an **integer**. So it cannot be '26'. We know that it has to be greater than '19' but less than '26' and we can find the '50%' of that number.
* Only possible no. is '24'. It has to be '24'.

![image](https://github.com/user-attachments/assets/3a2db3bb-91c5-461e-a131-97c71d7ff8b2)
![image](https://github.com/user-attachments/assets/41e8fd93-af8f-4793-93b3-2701e96fdf8d)
![image](https://github.com/user-attachments/assets/3ff20004-e53d-4f4c-9072-a7d781f9ff82)
![image](https://github.com/user-attachments/assets/0d155dc4-58a7-4d2a-9a8c-1fa20c71d0b3)

* We have to keep it less than '10%'. Max. is '10%'.
* Max -> 84. [3] [Answer] [**VERY IMPORTANT**] 

![image](https://github.com/user-attachments/assets/4bc615a3-724f-4ce4-8fbe-81a668d3d073)



































## Misc

![image](https://github.com/user-attachments/assets/5e53bb14-28f4-40a5-997b-727b1a446994)
![image](https://github.com/user-attachments/assets/173d9ae3-eb6e-4b07-9a45-849fed0ac976)
