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







## Misc

![image](https://github.com/user-attachments/assets/5e53bb14-28f4-40a5-997b-727b1a446994)
