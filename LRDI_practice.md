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

![image](https://github.com/user-attachments/assets/64355315-9513-4c46-9668-e4eee81363f7)
![image](https://github.com/user-attachments/assets/6eb141f0-96ab-412e-9dfb-3b47a9221247)

* All wickets were clean bowled.
* [Question]

![image](https://github.com/user-attachments/assets/367776af-0082-4969-9773-506187f6a0d6)

* 'J' had only '1' spell which means he bowled all his overs at once consecutively.
* The last over is bowler by 'S' because he bowled '12.1' overs which is '12' complete overs and '1' ball of his '13th over'.
* '12.1' over ball is a **wicket ball** as the over ended there only and no further balls were bowled.

![image](https://github.com/user-attachments/assets/1e5f5064-2f01-4694-b94f-d569e50c61c9)

* All of the '26' overs are mapped by who bowled which over.

![image](https://github.com/user-attachments/assets/2c644853-28a0-44b7-bade-b7d240b5c1d0)

* Maiden over -> No runs or '0' runs.

![image](https://github.com/user-attachments/assets/f0e662d8-5e41-4072-977b-9ded570d3e7e)
![image](https://github.com/user-attachments/assets/86dae039-f612-4435-9301-ffedb3d773ac)

* No. of boundaries scored by all of the batsman -> 1 + 2 + 1 + 1 + 1 + 1 + 1 + 2 + 1 -> 2 * 2 + 1 * 7 -> 4 + 7 -> 11
* 'M' is giving '7' 4s. 'M' takes '1' wicket only. 'M' can bowl to a max. of '3' batters.

![image](https://github.com/user-attachments/assets/2e6ddf4c-1a9d-46e9-9c08-d1b89bbc33e6)

* Max '4s' hit by a batter is '2' only.

![image](https://github.com/user-attachments/assets/6723e625-d89c-408b-91f3-244166152ea8)

* To score '7' boundaries(4s) in '2' overs we need max. of '5' batsman because '1' batsman can score a max. of '2' boundaries(4s) only.

![image](https://github.com/user-attachments/assets/e53c5118-aa36-4780-b5a4-d0f6b2223243)

* There are only '2' batters who can score a max. of '2' boundaries(4s).
* 'M' starts bowling from over '13'.
* 'SD' has to score his '2' boundaries(4s) against 'M' only which means that 'SD' cannot score any runs for the overs from '1 to 12'.

![image](https://github.com/user-attachments/assets/fd9e8d28-e05d-4d5e-ae61-2ac2125e2ad4)

* 'J' -> 15 runs -> 15 singles/ 1 four + 11singles/ 2 four + 7singles/ 3 four + 3singles.

![image](https://github.com/user-attachments/assets/b1e6581f-ca5b-4bf6-86b4-bd58efef45d4)

* 'S'.

![image](https://github.com/user-attachments/assets/7b6e4710-9f95-469f-9e8d-506cd9e9f4af)

* In 'J' overs more than '1' single(1) is not possible.

![image](https://github.com/user-attachments/assets/b9d25a33-5044-4f35-83fa-d5df715691d3)

* FOW -> Fall Of Wickets.
* 'J' conceided '15' runs in his '6' overs and he completed them within the 12 overs so we will score atleast '15' runs within the 12 overs.
* 12 - 6 -> 6 overs left.
* The rest '6' overs were bowled by 'S' and even if he got '2' maiden overs then in the rest '4' overs of 'S', he atleast conceided '1' run every over as they are not maiden overs.
* 4 * 1 -> 4 runs.
* 15 + 4 -> 19 runs -> In the '12' overs.
* 'SR' has come out to bat. 'SD' has not scored any runs.

![image](https://github.com/user-attachments/assets/2ea1a7d0-13af-4cb6-8134-b8f7d427b252)

* 'SR' has scored '1' run.
* At the '12th over', 'SD and SR' are batting together.

![image](https://github.com/user-attachments/assets/4b717a91-2e6e-4ace-b6a5-a0cf7dfa6b58)

* 'J' has conceided '3' 4s, so they are not scored by 'SD', they are scored by other batters.

![image](https://github.com/user-attachments/assets/d162ff25-1a0b-4240-8d03-bd326c70fd9c)
![image](https://github.com/user-attachments/assets/692f2c8b-6937-4228-9bb5-c1c059f1fb40)

* As 'SD' has not scored any runs in the '12 overs' so whenever he is on strike that over is going to a maiden over then 'S' will have '3' maiden overs which is **not possible**. 'S' can have '2' maiden overs only. So, in the '12th over' which is bowled by 'J', '1' boundary(4) is conceided by 'J'.
* One of the boundary(4) conceided by 'J' is at the '12th over'.

![image](https://github.com/user-attachments/assets/f7b25985-cd1c-4989-aa62-3bdbed26dbf5)

* We are not aware if 'SR' is out or not.
* In the '6' overs 'S' has bowled in the '12 overs', he can conceided atleast '4' runs.
* 'S' is left to conceided '10' more runs as he has conceided '14' runs in the whole match.

![image](https://github.com/user-attachments/assets/65aef0ec-b12c-4503-a825-57895e76935a)

* 'SR' scored the bounday in the 12th over.

![image](https://github.com/user-attachments/assets/2a966763-a918-41c7-9ca3-de2f5fc80e08)

* Min. boundaries from 13th to 26th over -> '7' boundaries -> 2 of SD, 1 of MSD, 1 of RJ, 2 of RA, 1 of BK.

![image](https://github.com/user-attachments/assets/305af981-ada3-48f5-ad23-15b7709e6094)

* 'SR' got out on the 12th over.
* 'SD and MSD' are batting on 13th over. 'SD' is on strike.
* '15' runs given by 'J' in the '12' overs and the rest '8' runs given by 'S' in the '12' overs.
* Total runs in the '12' overs -> 15 + 8 -> 23 runs.

![image](https://github.com/user-attachments/assets/beb19f5c-cd03-4b88-8812-b4eb687908be)

* 'S' gave '8' runs in the '12' overs. 
* 'S' gave '6' runs in rest of the overs. 

![image](https://github.com/user-attachments/assets/3ea2a1b4-e72e-4fa9-a265-bedb362a1e2c)

* '4' wickets fell in the overs from '1 to 12'. 'J' took '1' wicket and '3' taken by 'S'.
* Runs given in '13th' over by 'M' -> 4 * 4 + 1 -> 17 runs.
* 31 - 17 -> 14 runs left.

![image](https://github.com/user-attachments/assets/2c03f1d8-d8ce-4104-89cb-84756d633dc0)
![image](https://github.com/user-attachments/assets/c5ad0150-25ab-4aeb-a41d-5ecae1a262e6)

* 'RJ' will be on strike for '14th over'.
* RJ -> 5 runs
* MSD -> 4 runs.   
* 'MSD' is out in the '14th over'. 'RA' came next.
* 'RJ' was on strike for '15th over'.
* Runs given in '15th' over by 'M' -> 0 -> Maiden.
* 'RA' was on strike for '16th over'.
* Runs given in '16th' over by 'S' -> 1.
* RA -> 1.   
* 'RA' was on strike for '17th over'.
* Runs given in '17th' over by 'M' -> 0 -> Maiden.

![image](https://github.com/user-attachments/assets/020f6056-11a1-44fc-8867-15b23766f3e0)

* 'RJ' was on strike for '18th over'.
* Runs given in '18th' over by 'S' -> 1.

![image](https://github.com/user-attachments/assets/a593be27-d994-404f-82f8-1bf8eb9acbf3)
![image](https://github.com/user-attachments/assets/93a06187-6719-4c63-9fc0-bad2369baaac)
![image](https://github.com/user-attachments/assets/a3c4bbe6-be0d-43dc-85ae-16ce9aa112dc)

* 'RJ' was on strike for '19th over'.
* Runs given in '19th' over by 'M' -> 0 -> Maiden.
* 'RA' was on strike for '20th over'.
* Wickets taken in '20th' over by 'S' -> 1 -> RJ.
* Runs given in '20th' over by 'S' -> 1.

![image](https://github.com/user-attachments/assets/a9466772-3248-4fea-8988-2facb06879a0)
![image](https://github.com/user-attachments/assets/f8350aad-641c-431c-9cfc-c6b6fe7ad166)

* 'RA' was on strike for '21st over'.
* Runs given in '21st' over by 'M' -> 4 * 3 + 2 * 1 -> 14.
* 'BK' was on strike for '22nd over'.
* Runs given in '22nd' over by 'S' -> 1.
* Wickets taken in '22nd' over by 'S' -> 2 -> RA, UY.

![image](https://github.com/user-attachments/assets/4bd60dd6-0d90-4ffb-b9e5-31cbff77f927)
![image](https://github.com/user-attachments/assets/099e5fe9-3adc-4304-8490-7c388128279d)
![image](https://github.com/user-attachments/assets/42471562-0e0c-4104-899c-b82c1d28f26a)

* 'BK' was on strike for '23rd over'.
* Runs given in '23rd' over by 'M' -> 0 -> Maiden.
* 'MS' was on strike for '24th over'.
* Runs given in '24th' over by 'S' -> 1.

![image](https://github.com/user-attachments/assets/be3bb9f5-fc4b-4ef5-b658-2730c01e373e)

* 'MS' was on strike for '25th over'.
* Runs given in '23rd' over by 'M' -> 0 -> Maiden.
* 'BK' was on strike for '26th over'.
* Wickets taken in '26th' over by 'S' -> 1 -> BK.

![image](https://github.com/user-attachments/assets/8400dea5-afb2-400f-9cdc-4f36c7e6c1c7)
![image](https://github.com/user-attachments/assets/06dc887d-90c4-459f-a3c0-6fb1b568ee61)
![image](https://github.com/user-attachments/assets/13d7d26d-855b-4af4-b2c9-4d7212dc3b68)

* [**VERY IMPORTANT**] [Practice Again] [Concept]
* Answer -> option **A**. [1]
* Answer -> option **B**. [2]
* Answer -> 7. [3]
* Answer -> 44. [4]
* Answer -> Dhoni. [5]

![image](https://github.com/user-attachments/assets/0e45faec-52ab-4623-91a8-965dfc840e64)
![image](https://github.com/user-attachments/assets/8e4021c1-9fbd-4bd9-b079-aa23e097e7b6)

* [Question]

![image](https://github.com/user-attachments/assets/f4b38661-9b50-49ca-9378-bede0cd52071)

* Row-wise and column-wise -> '2' ticks and '1' cross for **both**.

![image](https://github.com/user-attachments/assets/7259a66c-eef8-4337-937e-752b442c17f5)
![image](https://github.com/user-attachments/assets/8a4bfca4-ee85-4d33-a69e-f0aae7529bbb)
![image](https://github.com/user-attachments/assets/93bdc13c-0094-406e-a7ab-8a9ddcfe052f)
![image](https://github.com/user-attachments/assets/a5525801-e2f0-42c6-b627-ae48bd54039a)
![image](https://github.com/user-attachments/assets/0592c44d-187c-4f4b-8d61-3757adc61088)

* Why not in the middle?
* middle -> 12 - 8 -> 4.

![image](https://github.com/user-attachments/assets/c84fb597-7519-4249-999b-ec9076d9eae5)
![image](https://github.com/user-attachments/assets/74b42eed-a3c0-4004-a74f-739a86b8a634)
![image](https://github.com/user-attachments/assets/86803097-0116-43d1-abee-9e6d260c6265)
![image](https://github.com/user-attachments/assets/64a28eee-b30c-45b5-ba2a-19bd5fc12120)

* Selection.

![image](https://github.com/user-attachments/assets/5b9886a2-ce48-415d-a6b1-3cce53484715)
![image](https://github.com/user-attachments/assets/cc91b8bc-2842-4ddc-9bfd-e8bdeb9a8545)

* Arrangement.

![image](https://github.com/user-attachments/assets/2a34ca81-fe85-4425-9cd0-6455cdd5da15)
![image](https://github.com/user-attachments/assets/e4898f41-0eb2-4873-b5c4-0e9bc3790453)

* [Question]

![image](https://github.com/user-attachments/assets/04ea1538-e693-427d-a7c6-cb6ed5810f94)
![image](https://github.com/user-attachments/assets/98a66c84-af2a-4ff6-9304-c4ac6ba92a61)

* Attacking points -> Task '1 and 3'.
* Sum of all the rank points -> 50 + 40 + 30 + 20 + 10 -> 150.

![image](https://github.com/user-attachments/assets/a95e71d5-0314-491a-a537-6ab24dc63ece)
![image](https://github.com/user-attachments/assets/784f8877-6253-4650-a851-abb771c41c8b)
![image](https://github.com/user-attachments/assets/302223f7-4ecf-4d0e-b985-25ea55d8c3f8)

* Time saves in task **1** -> 30 + 15 + 32 + 8 -> 85.
* x -> bonus points -> 19.
* 60 - 19 -> 41mins.

![image](https://github.com/user-attachments/assets/cf404a4d-55c3-40c9-a721-65efefe9206f)
![image](https://github.com/user-attachments/assets/3e5112ef-2a62-427d-af87-d8bd317eac47)

* Attacking points -> Task 'B and D'.

![image](https://github.com/user-attachments/assets/978efb85-166b-4181-aeb5-79068aa97cfb)
![image](https://github.com/user-attachments/assets/9b1362f9-dd36-4920-8c80-e65b200fddfb)

* Task B -> 20 + 20 + 30/20 + 20/10 + bonus points = 178.
* bonus points -> 15 + 3 + 4 + 2 -> 24.
* Total -> 178.
* 178 - 24 -> 154.
* We have  many possibilities.

![image](https://github.com/user-attachments/assets/e2a952bb-84bd-49d1-8bda-37a36770f80d)
![image](https://github.com/user-attachments/assets/7dc6933b-8122-4e70-8fc1-e0f294e1a31c)
![image](https://github.com/user-attachments/assets/7c632e6f-7891-4676-bd93-ab29ff362f50)
![image](https://github.com/user-attachments/assets/1902ce25-52ed-4659-8aea-8fbc18ec3164)

* Bonus -> 60 - 14 -> 46mins.
* If it is '46mins' then we are not getting rank '1'.
* This is **not possible**.

![image](https://github.com/user-attachments/assets/652eb998-5dd7-4cec-a474-38b20a21f3e3)

![image](https://github.com/user-attachments/assets/7d7a0404-e1b6-47ed-bf27-87a9fa293aa7)

* Bonus -> 60 - 24 -> 36mins.
* If it is '36mins' then we are not getting rank '2'.
* This is **not possible**.

![image](https://github.com/user-attachments/assets/3b263912-6394-4e91-b828-8c864954d5ec)

* '64' -> This is **not possible**.

![image](https://github.com/user-attachments/assets/8f2e6ca9-5c8e-4e23-b4be-fe7f2759c3ad)

* '74' -> This is **not possible**.

![image](https://github.com/user-attachments/assets/fcbf240e-95d0-4e44-977e-3d3300fa3cf8)
![image](https://github.com/user-attachments/assets/1dc52019-bd80-4be2-8a74-b8d216e5b79c)
![image](https://github.com/user-attachments/assets/3b0556ef-e991-4b44-8b19-37fb708a1ea2)

* We have to do this for task 'D' now.
* Task B -> 50 + 30 + 40 + 40/30 + bonus points = 286.
* bonus points -> 32 + 25 + 12 + 18 -> 87.
* Total -> 286.
* 286 - 87 -> 199.

![image](https://github.com/user-attachments/assets/a104c0db-6665-4e48-8c01-aacb5ab20818)
![image](https://github.com/user-attachments/assets/d8d1ac29-bce3-473a-9d1f-d27e7ac25ed8)

* We have '2' possibilities.

![image](https://github.com/user-attachments/assets/f7d5303d-fff7-4866-927f-b1bbaa53a4ab)
![image](https://github.com/user-attachments/assets/3b15bded-f630-442d-8526-9d264932dd02)
![image](https://github.com/user-attachments/assets/19fb03f9-49c8-4c44-bea9-327ae0799dde)
![image](https://github.com/user-attachments/assets/50b098ba-d8b8-4c22-99b0-f5d9e1861ca3)
![image](https://github.com/user-attachments/assets/9af18824-c6a7-4ae5-87c0-e5a72af65233)

* Solved. [**VERY IMPORTANT**] [Practice Again] 

![image](https://github.com/user-attachments/assets/dc296b0a-74f6-4b87-b66c-628e8964e1e7)
![image](https://github.com/user-attachments/assets/90357dbf-1abb-4dca-9289-925992c60ae1)

* Learning and Approach.

![image](https://github.com/user-attachments/assets/847ca8e9-da13-48e2-85fd-1f28f251f6dc)
![image](https://github.com/user-attachments/assets/8e5b4fd0-b8e2-48c6-8289-0173e6729360)

* Columnn is easy to solve/do.
* Row is difficult to solve/do.
* Attacking point should be **column** then **row**.
* We  know the rank is '150' for sure.

![image](https://github.com/user-attachments/assets/51a91483-11f0-4fb2-b75b-4b66ede9689f)
![image](https://github.com/user-attachments/assets/f496a7d4-142d-4287-a213-c23aac73ce91)
![image](https://github.com/user-attachments/assets/5e429eec-9583-4294-a8a3-bb0df65d6030)
![image](https://github.com/user-attachments/assets/4a7318b2-4042-42f9-84aa-0bb0b42aab69)
![image](https://github.com/user-attachments/assets/b444a50a-f4a0-4f58-b579-aefc886ec3a9)

* Max/Min.
* [Question]
* All of the questions are from '2010 to 2016'.

![image](https://github.com/user-attachments/assets/4f8456e5-9452-460d-a8b5-2cd10a365dd7)

* Atmost 30 -> Less than 30 -> 2 + 3 + 1 + 3 + 2 -> 11 -> Not less than '10' -> Not need to hire more employees.

![image](https://github.com/user-attachments/assets/abd522f3-88e6-4d48-9da2-f36473b6cbd6)

* More than 30 and atmost 40 -> 2 + 1 + 1 + 6 -> 10 -> Not less than '10' -> Not need to hire more employees..

![image](https://github.com/user-attachments/assets/7043899e-db96-416d-9c79-13262be67a11)
![image](https://github.com/user-attachments/assets/150b9f02-99b9-4751-b4e7-c2f919f8d5f7)

* Less than 30(2012) -> 2 + 3 + 1 -> 7 -> less than '10' -> Need to hire more employees.

![image](https://github.com/user-attachments/assets/f3006e4a-239c-4ad2-8173-fd1c5cfc206e)
![image](https://github.com/user-attachments/assets/92ecf40f-6838-4ea5-b80f-ac1058499791)

* Less than 30(2013) -> 3 + 2 + 3 + 1 -> 9 -> less than '10' -> Need to hire more employees.
* 30 to 40(2013) -> 3 + 2 + 2 + 1 + 1 -> 9 -> less than '10' -> Need to hire more employees.

![image](https://github.com/user-attachments/assets/7d22cd0e-0ec0-4417-9644-da3295385a9b)

* Less than 30(2014) -> 3 + 3 + 2 + 3 -> 11 -> Not less than '10' -> No Need to hire more employees.
* 30 to 40(2014) -> 1 + 3 + 2 + 2 + 1 + 1 -> 10 -> Not less than '10' -> No Need to hire more employees.

![image](https://github.com/user-attachments/assets/356d17e8-b862-4fcf-a3de-6107fbd8e874)

* People crossed '50yrs', make those people **retire**.

![image](https://github.com/user-attachments/assets/ffc72cbe-ef79-4810-a15d-9274acbee2e8)
![image](https://github.com/user-attachments/assets/0a206e17-a69f-4a80-ae39-ef6aafbfff50)

* Less than 30(2015) -> 3 + 3 + 2 + 3 -> 11 -> Not less than '10' -> No Need to hire more employees.
* 30 to 40(2015) -> 1 + 3 + 2 + 2 + 1 + 1 -> 10 -> Not less than '10' -> No Need to hire more employees.

![image](https://github.com/user-attachments/assets/73480750-4c57-4606-b144-cf0b7f9b9fe5)

* Less than 30(2016) -> 3 + 3 + 2 + 3 -> 11 -> Not less than '10' -> No Need to hire more employees.
* 30 to 40(2016) -> 1 + 3 + 2 + 2 + 1 + 2 -> 11 -> 
 Not less than '10' -> No Need to hire more employees.

![image](https://github.com/user-attachments/assets/1f63a120-89b6-469d-a689-c6a3a4375c15)
![image](https://github.com/user-attachments/assets/52a29dc1-8f7d-4084-91ed-01b4f9cce989)
![image](https://github.com/user-attachments/assets/a3d0b3db-d10d-44e8-ae1d-104fef9c21c4)

* New hires -> 3 + 3 + 2 -> 8. [1] [Answer]

![image](https://github.com/user-attachments/assets/f86b3b84-c649-444d-88c0-09b23a9646e8)

* Answer -> 32. [2] [Answer]

![image](https://github.com/user-attachments/assets/452fb4ca-6dbb-47d7-9d31-13cea8891abf)

* [3] [Answer]

![image](https://github.com/user-attachments/assets/57f4430f-354c-48cf-a436-cc1e35642e75)

* [4] [Answer]

![image](https://github.com/user-attachments/assets/74ad9120-b6e5-4cea-8be1-e4bcc176cdba)
![image](https://github.com/user-attachments/assets/700308fe-0852-4cfc-8f40-96aaceb3105b)
![image](https://github.com/user-attachments/assets/60d9db8d-f130-4ea3-8571-069214e187c8)
![image](https://github.com/user-attachments/assets/6da6b356-ae44-49e5-be53-7cce8a3e0ab8)

* [Question]
* We have to create a **table**.

![image](https://github.com/user-attachments/assets/5dba2ee0-a50b-461d-8728-686a16c0c5a8)

* 10% of 100a -> 110a
* 20% of 100a -> 120a
* Total tax -> 17518500
* Tax per person **same** -> 100a.
* No. of people -> 3n.

![image](https://github.com/user-attachments/assets/4129677a-4c97-451f-9ba4-0ddb1b397ef4)
![image](https://github.com/user-attachments/assets/ea2e19ad-26c7-4d1b-b405-736f65c794d7)

* Taxes of pensioners under '5L' should be -> 100na

![image](https://github.com/user-attachments/assets/4ffeba6a-f404-47a1-bb31-6d4e9cd63b3e)
![image](https://github.com/user-attachments/assets/34ff4542-dbf3-4104-8425-7ebfb8a13806)

* Taxes of pensioners under '5L' is-> 50a -> 50a * 2n -> 100na.
* No. of people -> 2n.
* Holding point '3' for now.

![image](https://github.com/user-attachments/assets/4212a626-908f-4ec2-94ed-a5f4e74e1fbf)
![image](https://github.com/user-attachments/assets/b0b88547-bfdc-4ea2-830b-bbf285095d85)

* From point '4'.
*  Tax collection from bussinessmen under '5L' -> c * 120a.
*  Tax collection from bussinessmen '5L to 10L' -> d * 132a.
* Tax collection from bussinessmen for '10L+' -> e * 144a.
* For explaination. Not needed.

![image](https://github.com/user-attachments/assets/eb1b8d71-11b5-4332-858f-f35ba48a8110)

* y = x * 120a.
* y/120a = x.
* x -> No. of people.

![image](https://github.com/user-attachments/assets/e3e80d3d-3a87-44ec-8492-77fb5e334c6d)

* Total tax by pensioners -> 330na.
* No. of pensioners -> 3 * 2n -> 6n.

![image](https://github.com/user-attachments/assets/1ba76d3b-a29d-4a4a-b6b2-4d79998a3071)

* a = 15.

![image](https://github.com/user-attachments/assets/589120ae-748d-4da9-8c69-f6f76f126dc2)
![image](https://github.com/user-attachments/assets/34c12ff2-4c10-48ca-a308-fbe242333577)
![image](https://github.com/user-attachments/assets/292988aa-1ea4-4c7e-befc-77dc36418372)

* a = 15.
* y = 4752000 -> option **D**. [5] [Answer]

![image](https://github.com/user-attachments/assets/d1b9f8c8-f964-4fac-96bf-97a93cfcc37e)
![image](https://github.com/user-attachments/assets/9661e8a6-c792-4b6b-b510-8329c6f0e0f8)

* '3' bussiness tax are **same** -> 3y.

![image](https://github.com/user-attachments/assets/c992d185-6d00-4774-b4ea-952bd4c02126)
![image](https://github.com/user-attachments/assets/9aed0a58-c49e-4113-a284-a78af229fcf0)

* n = 150.
* Total no. of people -> 3 * 2n + 3n + 2n + 5n + 7240 -> 16n -> 150 * 16 + 7240 -> 9640. [4] [Answer]

![image](https://github.com/user-attachments/assets/2882be4b-88f3-486e-a8b1-8d0f571da71d)
![image](https://github.com/user-attachments/assets/0e81bfcc-9b2f-400e-98be-cb824cc560f6)

* 132a = 132 * 15 = 1980. [1] [Answer]

![image](https://github.com/user-attachments/assets/5ff08dc6-e2ca-4ebb-a712-9eab3da8420a)

* Total tax by salaried persons -> 1120na -> 1120 * 150 * 15 -> 25,20,000. [2] [Answer]
* Total tax by bussiness persons -> 1,45,26,000.
* Total tax by pensioned persons -> 330na -> 330 * 150 * 15 -> 7,42,500 [2] [Answer]
* Diff -> Highest - Lowest -> 1,45,26,000 - 7,42,500 -> 1,37,83,500.
* %more -> (1,37,83,500/1,45,26,000) * 100 -> 94.8884758364 -> 94.88% [3] [Answer]
* The options are different.

![image](https://github.com/user-attachments/assets/ff63939e-3bff-4b70-b145-28e315b7e5d8)
![image](https://github.com/user-attachments/assets/cb2ba661-17ea-4a04-9f12-c4b557aa0719)

* [Question]

![image](https://github.com/user-attachments/assets/6fde7e50-5ac6-4a8a-af73-7256e7e209df)

* 'N' has taught '2' diff. subjects.
* 'M' has taught '2' diff. subjects.

![image](https://github.com/user-attachments/assets/744bf61b-a3e0-42c5-909f-693986474c3e)
![image](https://github.com/user-attachments/assets/e70822a3-c4c1-45df-b44b-7fa97f27387f)

* No match between 'q and y'.
* No match between 'b and d'.
* We need to accomodate '3' DIs.
* Between 'q and y', we will put 'DI'.
* Between 'b and d', we will put 'DI'.
* Answer -> option **B**. [1] [Answer]

![image](https://github.com/user-attachments/assets/356059e4-b160-4a06-9e3f-af4ebb481863)
![image](https://github.com/user-attachments/assets/716801a2-b258-46b1-a992-83d7852accad)
![image](https://github.com/user-attachments/assets/cceec535-1485-41d9-8224-4aca77877e82)
![image](https://github.com/user-attachments/assets/a43aca59-5be2-47fa-a143-b50e94953f85)
![image](https://github.com/user-attachments/assets/39f33245-0592-48dd-9fbc-f596d0a8fe42)
![image](https://github.com/user-attachments/assets/f8a29e04-7f78-4a9b-bf8f-c22b6f845ff5)

* Multiple possibilities.
* Option **D** has to be **True**. [2] [Answer]
* Must be True -> has to be **True** -> Guranteed/100%. [Concept] [Logic] [Meaning]

![image](https://github.com/user-attachments/assets/a80e8129-4a59-4773-b56b-30c26532ecd0)
![image](https://github.com/user-attachments/assets/d542e0c9-7bca-41e0-9c88-011485f168bd)

* 'P, x, q, y' have to be **differet**.
* 'x, q, y' are 'QA, VA/DI, DI/VA'.
* 'P' has to be 'LR' that's the only '1' left.
* 'a, b, c, d' have to be **different**.

![image](https://github.com/user-attachments/assets/d543f381-daf8-40a1-acd2-f53e333c5aca)

* 'QA' is happening once(1).
* Could be True -> Possibility. [Concept] [Logic] [Meaning]
* Option **A** -> Possibility. 
* Option **B** -> Not Possible.
* Option **C** -> Not Possible.
* Option **D** -> Not Possible.

![image](https://github.com/user-attachments/assets/9eeb2929-df9e-4a29-93a8-d6cd89691635)

*  Option **A**. [3] [Answer]

![image](https://github.com/user-attachments/assets/3a40fc7b-e9e1-4430-9ca0-5b730345181f)

* True Except -> Find the **false/incorrect** option. [Concept] [Logic] [Meaning]
* 'P, x, q, y' have to be **differet**.
* 'a, b, c, d' have to be **different**.

![image](https://github.com/user-attachments/assets/aa64715a-53f8-4ad4-80b4-f0711b8d793a)

* Option **A** -> True. 
* Option **B** -> True.
* Option **C** -> True.
* Option **D** -> False.

![image](https://github.com/user-attachments/assets/dc357c74-6ba5-4a52-abe8-3550b839138f)

*  Option **D**. [4] [Answer]

![image](https://github.com/user-attachments/assets/929eca76-9fdf-4436-aad4-5faf06d31a9c)
![image](https://github.com/user-attachments/assets/aec0efc3-3b17-4bc9-9e26-962ac1d792b2)
![image](https://github.com/user-attachments/assets/e6cbd975-53d9-4da6-91e6-89af2f0503ba)

* [Question]

![image](https://github.com/user-attachments/assets/020df78c-3854-4551-a8ec-0fd940ee081b)

* The orders that were booked on '11th' would be marked as lost on '13th'. '12th' is 'day 1' of delivery and '13th' is 'day 2' of delivery.
* 14th -> 249 - 219 -> 30.

![image](https://github.com/user-attachments/assets/8afd8885-3e30-4616-8d17-45e87c2c7b32)
![image](https://github.com/user-attachments/assets/53b7af3f-ecb9-4043-bb9f-503d3cb81ab0)

* 14th -> 92 - 91 -> 1
* 15th -> 94 - 92 -> 2

![image](https://github.com/user-attachments/assets/bcb5a82a-b3f0-4d67-8cbb-a0b4f61052a6)

* 11th + 2day delivery -> 13th
* 12th + 2day delivery -> 14th
* 13th + 2day delivery -> 15th

![image](https://github.com/user-attachments/assets/1d991dec-5392-48e3-b2da-7d187c18e4bd)
![image](https://github.com/user-attachments/assets/2e68b7dc-e5de-4b88-8d02-96b36f43f930)

* 'x' item orders booked on '12th'.
* x = day '1' delivery + day '2' delivery + lost.

![image](https://github.com/user-attachments/assets/db724693-d658-4ba2-be32-8691b8043065)
![image](https://github.com/user-attachments/assets/e7106e10-793b-4167-b62a-21bf3ccb0509)

* 11 - 4 -> 7.
* 27 - 6 -> 21.
* 23 - 8 -> 15.
* 13th orders -> 21 + 8 + 2 -> 31.
* x = 7 + 6 + 1 = 14.

![image](https://github.com/user-attachments/assets/73576372-bdab-43eb-88e9-f16ee1429768)

* 14th orders -> 30.
* 30 = 15 + day '2' delivery + 12 -> y = 30 - 27.
* y = 3.
* 16th's day '2' delivery -> y = 3.

![image](https://github.com/user-attachments/assets/0667ac15-8eb3-47c7-bed0-3d573709f24d)

* 16th orders delivered -> 11 - 3 -> 8.

* 15th orders -> 28.
* 28 = 8 + day '2' delivery + 12 -> y = 28 - 20.
* y = 8.
* 17th's day '2' delivery -> y = 8.
* 17th orders delivered -> 21 - 8 -> 13 .

![image](https://github.com/user-attachments/assets/60431dc6-5a33-4eca-9dfb-30af5e94b832)
![image](https://github.com/user-attachments/assets/fa4120e8-0e6c-4ab9-b99a-7e5c0f16f409)

* 14th orders booked -> 30.
* 14th orders lost -> 12.
* 13th orders booked -> 31.
* 13th orders lost -> 2.
* 15th orders booked -> 28.
* 15th orders lost -> 12.
* 16th orders booked -> 25.
* 16th orders lost -> 2.

![image](https://github.com/user-attachments/assets/882dc11f-bdf8-414f-92c1-73cf4f513d14)
![image](https://github.com/user-attachments/assets/5b299bc0-07df-4d65-aa73-bd6fced62d28)

* [1] [Answer]
* Answer -> 13th. [2] [Answer]
* Sum + 12 + 2 + 9 -> 23. [3] [Answer]

![image](https://github.com/user-attachments/assets/c44b9f52-05d5-406d-b936-4d0f41c7604c)
![image](https://github.com/user-attachments/assets/c4e44f60-0df7-4cc2-b5d9-afd70bd70c85)

* 13th orders booked -> 31.
* 13th orders delivered on day '1' -> 21.
* 13th orders delivered on day '2' -> 8.
* 14th orders delivered on day '1' -> 15.
* 14th orders delivered on day '2' -> 3 .
* 15th orders delivered on day '1' -> 8.
* 15th orders delivered on day '2' -> 8 .
* 16th orders delivered on day '1' -> 13.
* 16th orders delivered on day '2' -> 10 .
* Answer -> 14th. [4] [Answer]

![image](https://github.com/user-attachments/assets/f189cdcb-e487-4f43-836e-d7a3e28b1034)
![image](https://github.com/user-attachments/assets/114da54d-9f25-429d-a89f-c5d9f43df345)
![image](https://github.com/user-attachments/assets/7ec02195-b662-48eb-8c61-6381d2fdd9c4)

* day '1' -> x.
* day '2' -> y.
* Answer -> 14th. [5] [Answer]

![image](https://github.com/user-attachments/assets/bb5c0286-444c-42df-937a-0d806efff2be)
![image](https://github.com/user-attachments/assets/9a7536c7-2abe-4fd3-83f7-bac542cb72e4)
![image](https://github.com/user-attachments/assets/24e70f69-e051-4716-a396-1211bdc96395)

* [Question]

![image](https://github.com/user-attachments/assets/2c37e2db-84a0-4590-b470-dfdab758e3e4)
![image](https://github.com/user-attachments/assets/58843be4-e3b8-4db1-be34-8b2a58611e7a)

* All are distinct.
* We don't know the **exact** values.
* No. of **test** matches and **ODI** matches cannot be **equal/same**.
* ODI match fees < test match fees.
* If we want **min. match fees** then we have to take **less test matches and more ODI matches** as the match fees for test match is more than ODI match.

![image](https://github.com/user-attachments/assets/6e197945-0f8d-42ec-89ed-b5fc12bc1677)

* Min. match fees -> 5T + 6ODIs -> 2.45Cr -> satisfied.
* Min. match fees -> 6T + 5ODIs -> 6 * 0.25 + 5 * 0.2 ->  2.5Cr -> Not satisfied.
* 2.45Cr < 2.5Cr.
* Every cricketer is getting min. of '2.45Cr'.

![image](https://github.com/user-attachments/assets/a4138ccf-7413-42e3-9e94-a8726632d8e3)

* 7.3 - 2.45 -> 4.85Cr.

![image](https://github.com/user-attachments/assets/41db800a-eea7-4729-84e9-259963ac6f85)

* Virat -> Not 'A or B', he is 'C' -> He has **min. bal** of '4.85Cr'. For 'B' he needs '5Cr'.

![image](https://github.com/user-attachments/assets/c5f44e14-5f80-4c61-86e9-e498ce553f52)
![image](https://github.com/user-attachments/assets/78fb86bf-54a0-4013-90e6-82a571df4370)

* If we want **max. match fees** then we have to take **more test matches and less ODI matches** as the match fees for test match is more than ODI match.
* Virat -> 'C' contract confirmed.
* Rahane -> 'C' contract confirmed.
* We don't have to do max. bal for them(Virat, Rahane).
* Rohit -> 7.75 - 4.3 -> 3.45
* KL -> 8.4 - 4.3 -> 4.1
* '4.3Cr' is the **max. match fees** one cricketer can receive. It cannot be more than that.

![image](https://github.com/user-attachments/assets/63b5e4bf-01d7-488d-afb0-a47c4a43e94e)

* Balance(bal).
* Bumrah match fees is lying between '5.15Cr to 7Cr'.

![image](https://github.com/user-attachments/assets/0317fb5f-c393-4bba-83c7-d80f52b6ec2d)
![image](https://github.com/user-attachments/assets/e1917b12-f18f-4be7-a375-148add206c41)

* If Bumrah is in 'B' then his fees is '9.3Cr' but in the question it is '9.45Cr'. So Bumrah is in 'A'.

![image](https://github.com/user-attachments/assets/32093efc-506d-429b-8f2e-ad9ff8b82a18)
![image](https://github.com/user-attachments/assets/d919c4e8-7a13-4033-a406-cfad9c24c072)

* If Rohit is in 'C' then his fees is '7.3Cr' but in the question it is '7.75Cr'. So Rohit is in 'B'.
* Band -> Min. match fees and Max. match fees. [Logic] [Concept] [**VERY IMPORTANT**]

![image](https://github.com/user-attachments/assets/9a792f44-a877-4638-9993-0be181fb554c)
![image](https://github.com/user-attachments/assets/87dfc62f-b6eb-4ef2-8191-2a5bce417d4f)
![image](https://github.com/user-attachments/assets/ed19418d-1b5d-4c13-9371-00d5560c8422)

* Actual match fees of Virat -> 7.3 - 3 -> 4.3Cr ['C' -> 3Cr]
* Actual match fees of Rohit -> 7.75 - 5 -> 2.75Cr ['B' -> 5Cr]
* Actual match fees of Bumrah -> 9.45 - 7 -> 2.45Cr ['A' -> 7Cr]

![image](https://github.com/user-attachments/assets/fcc21077-e114-4b6b-9a4a-25b0af0474ed)
![image](https://github.com/user-attachments/assets/e7bd0e16-fae8-4a24-9675-476bb2b2122c)

* Virat -> 10 * 0.25 + 9 * 0.2 -> 2.5 + 1.8 -> 4.3Cr
* Bumrah -> 5 * 0.25 + 6 * 0.2 -> 1.25 + 1.2 -> 2.45Cr

![image](https://github.com/user-attachments/assets/fc2184d8-6617-42ce-864f-689216b60385)
![image](https://github.com/user-attachments/assets/60cfeea7-b962-4990-a7e1-d94130d064e1)

* 4y = 20 -> y = 5.
* Multiplying Factor(MF) -> 100/5 -> 20.
* 3.4 * 20 -> 68.
* 3.5 * 20 -> 70.
* 3.85 * 20 -> 77.

![image](https://github.com/user-attachments/assets/7ddad73f-4827-4351-b25f-c07bb05a1bec)

* Questions.
* We want the no. of tests matches for the cricketers to be distinct.
* We want the no. of ODI matches for the cricketers to be distinct.
* We want the no. of tests and ODI matches for the particular cricketers to be distinct.

![image](https://github.com/user-attachments/assets/31936221-6a5a-4e3d-bbf2-09b41ae9bb81)
![image](https://github.com/user-attachments/assets/89f7ca84-ca5a-472c-a577-ed509b97bafd)

* Question **4** solution.

![image](https://github.com/user-attachments/assets/153cd4c3-20fd-4cdb-838e-c1d7302ed8bd)

* T -> 10 - 2 -> 8.
* O -> 9 - 1 -> 8.

![image](https://github.com/user-attachments/assets/0538cc46-f019-4850-8cd4-6274affa9c00)

* As Rohit and Ashwin are in same 'A' contract and ashwin has played more matches than rohit, so no point in calculating rohit. We can **remove rohit from the options**. Just calculate for **ashwin**.

![image](https://github.com/user-attachments/assets/004d361b-195d-4d00-a7fe-60a4fb365e6f)
![image](https://github.com/user-attachments/assets/8da34d03-f9a6-4bbf-86ea-36e8e2380b2d)

* Ashwin is 'A', so he is '7Cr' plus.
* Answer -> Ashwin -> option **4**. [4] [Answer]


























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
![image](https://github.com/user-attachments/assets/2f6a4715-d78b-4294-9d4d-17e5827a6cbe)

* [Question]

![image](https://github.com/user-attachments/assets/f65369f5-085d-49c3-b041-88d77411f999)

* Total matches -> 15.
* R1 -> 6.
* R2 -> 15 - 6 -> 9.
* We have '6' teams, '6' matches in 'R1'. We have '6 * 2 -> 12' slots in 'R1'. So each team is playing '2' matches in 'R1'.
* Each team will occur '2' times.
* We have '6' teams, '9' matches in 'R2'. We have '9 * 2 -> 18' slots in 'R2'. So each team is playing '3' matches in 'R2'.
* Each team will occur '3' times.

![image](https://github.com/user-attachments/assets/e34e807f-7241-46b6-b9c2-d483c99ca0d9)

* '2' points are being distributed per match.
* 15M -> 15 * 2 -> 30 points.
* Tie -> '1' or '0'.

![image](https://github.com/user-attachments/assets/5f97b3e4-eb27-4c44-963b-fa840d6be515)
![image](https://github.com/user-attachments/assets/9533a67b-0f1a-415f-97d7-961737cff2fc)
![image](https://github.com/user-attachments/assets/4ab226d6-a9ab-413c-b64b-09eddc4a3589)

* B - E, B - F -> They are not possible.

![image](https://github.com/user-attachments/assets/4b4db69a-c4ca-4925-bfae-ebea9957cc48)
![image](https://github.com/user-attachments/assets/1b4c2393-aead-4b84-a855-5d2321be04f2)
![image](https://github.com/user-attachments/assets/8d66b533-71af-4e1c-9709-8d7a9ccd60a1)

* End of Round '1'.

![image](https://github.com/user-attachments/assets/406468d8-f45d-461a-a667-e15a25b98a5c)

* 'A' has already played against 'C and E' in 'R1'. So 'A' is playing against 'B,D and F' in 'R2'.
* As there was a tie in 'R1' between 'E and F'. So in 'R2', 'E and F' cannot have a tie.
* 'B' lost against 'F' in 'R1' so 'B' cannot be the winner.
* 'A and D' got '1' tie in 'R2'.
* 'E and F' got '1' tie in 'R1'.
* 'B' cannot be the winner.
* 'C' got the least no. of ties in the tournament.
* 'C' is the winner of the tournament.
* 'C' will have the max. score at the end.

![image](https://github.com/user-attachments/assets/0555da81-f2db-49b0-b97b-667148b03684)
![image](https://github.com/user-attachments/assets/badc44a9-e8fa-40fc-b330-041142320b91)

* All of them have to be **less than '6'** for 'C' to be the winner.

![image](https://github.com/user-attachments/assets/aad3db35-e413-4291-b1a8-66ab96b80307)
![image](https://github.com/user-attachments/assets/8621b8f9-9f45-4238-8a9e-0c6c3adbeb2a)

* If 'A' wins in 'A - B' then 'A' will have '7' points which is **not possible** as 'C' is the **winner**. So 'A' losses against 'B'.

![image](https://github.com/user-attachments/assets/610bfdec-d4c4-41c3-9801-380c5b3e2f7d)
![image](https://github.com/user-attachments/assets/02e189b1-4334-40c7-8788-5d73f9e91c10)
![image](https://github.com/user-attachments/assets/9c045b43-430e-4109-a75f-8d11b18e9769)
![image](https://github.com/user-attachments/assets/5eedadce-3f5d-4198-99c7-11da0456c179)

* A,D,E,F -> 5. [1] [Answer]

![image](https://github.com/user-attachments/assets/674d284c-e9a4-4e00-85dd-d7b1abcf339a)

* [Question]

![image](https://github.com/user-attachments/assets/d4be4150-83bb-42db-84b6-00c25c76746a)
![image](https://github.com/user-attachments/assets/a400360a-e282-4fd3-9573-3c39c9369cee)

* Both things are **same**.

![image](https://github.com/user-attachments/assets/73a48513-9d33-48e1-8c77-373d3437dd13)

* Stage 1 -> Green Color.
* Stage 2 -> Red Color.
* 'B, C, D, E, F -> All of them have lost atleast once in Stage '1'. 'A' has not lost atleast once in Stage '1'.   
* 'A' has won all of the '3' matches.
* 'F VS A' match did not happen in Stage '1'.

![image](https://github.com/user-attachments/assets/c32a6050-0698-48eb-999c-8c075058cdcd)

* 'B and F' lost their '2' matches in Stage '1'. Others have won atleast once in Stage '1'.
* '2' teams lost all their matches -> 'B and F'.
* 'F VS C' match did not happen in Stage '1' as no ties are possible and both 'F VS C' lost all matches in Stage '1'.
* 'F VS B' match happened and 'F' lost.

![image](https://github.com/user-attachments/assets/728e38af-7405-460e-a09a-4840aa84df25)
![image](https://github.com/user-attachments/assets/79ee25f3-d892-4107-b5b3-4e03f3350f7a)
![image](https://github.com/user-attachments/assets/42953bc3-913b-4213-936d-031f775c872e)

* Stage '1'.

![image](https://github.com/user-attachments/assets/c7258117-203b-4a0c-a1be-a8628d8f01a5)
![image](https://github.com/user-attachments/assets/ca1ba11f-156e-4faa-a6b3-2db98a1e811b)

* As 'F' won '1' match in Stage '2', so 'C' will lose both(2) matches in Stage '2'. 'F' will win it's remaining '1' match in Stage '2'.

![image](https://github.com/user-attachments/assets/cd94a391-8efc-49c4-9725-6b0d4ea9484e)

* 'D' lost both(2) matches in Stage '2'.

![image](https://github.com/user-attachments/assets/e27d1224-e338-413d-9268-6f2c0f707f05)
![image](https://github.com/user-attachments/assets/65e4e646-1ce5-4c1f-b415-982242a2c786)

* Stage '2'.
* Stage '1' leader -> A.

![image](https://github.com/user-attachments/assets/721c3baf-0819-4a14-86d6-db377a8adb02)
![image](https://github.com/user-attachments/assets/2f666225-89ff-4017-967d-d2a906b8eec5)
![image](https://github.com/user-attachments/assets/e08402e1-3a21-4024-8f06-804581fd11be)
![image](https://github.com/user-attachments/assets/b6436ab4-2010-4734-b4d4-978f21162deb)

* [Answers]

![image](https://github.com/user-attachments/assets/d3569c69-9cc1-43e4-867d-495842c93696)

* [Question]

![image](https://github.com/user-attachments/assets/7683e377-f493-4b6b-b0de-55da59a3e80d)
![image](https://github.com/user-attachments/assets/9ca13685-2878-469b-b3a1-fe3348179f08)
![image](https://github.com/user-attachments/assets/638f79f7-ec90-4a8b-b3d3-afab39fefbce)
![image](https://github.com/user-attachments/assets/11328f59-2a8e-4125-b6b0-60b3a36a01c1)

* [Doubt]

![image](https://github.com/user-attachments/assets/52c3e02e-54e9-47d7-9f54-8b0f12beb683)

* [Answer]

![image](https://github.com/user-attachments/assets/5682e184-28c4-4688-a6dd-62402371fd6b)

* [Question]

![image](https://github.com/user-attachments/assets/cf78d779-db9a-4330-9456-18012f724814)

* 35/5 -> 7.
* The '4' are correct for both 'D and G'. Out of the rest '6', '3' of them are correct for 'D and G' respectively.
* 4 + 3 -> 7 -> Which we want.
* CC -> West -> This is **wrong**.
* CC -> South -> This is **correct**.
* Mall -> West -> This is **correct**.

![image](https://github.com/user-attachments/assets/9a30d1dc-83bf-4b13-8fcf-94b85d5c20fa)
![image](https://github.com/user-attachments/assets/9c9eb5fa-60bc-4d22-9248-760f43f251ac)
![image](https://github.com/user-attachments/assets/15695347-0a9e-42a7-81e1-92fa5b6145bd)
![image](https://github.com/user-attachments/assets/5a5511ce-5116-4b5f-b418-e0ed6fa8154a)

* [Answer]










### Practice Questions

![image](https://github.com/user-attachments/assets/0eee024c-1f5d-4ec5-9738-c1d1dc33dd87)

* [Question] [Practice Again] [Tricky Question]
* Question is talking about an **order**.

![image](https://github.com/user-attachments/assets/234588bc-c78b-4127-b7b7-fde2174bee79)
![image](https://github.com/user-attachments/assets/2329f86f-0d77-427b-854f-7ff999471a11)
![image](https://github.com/user-attachments/assets/917ab1c5-ce26-465f-97a9-638e1afd8c7d)

* At the '6th' order, **denominator** is '16'.
* At the '1st' order, we are assuming '16p' as it is a multiple of '16'. It is because we have '16' as **denominator**.

![image](https://github.com/user-attachments/assets/3cc378c8-e733-49f9-94c3-4b5c92a45818)
![image](https://github.com/user-attachments/assets/f4d1cc1d-ba91-4f34-a704-e67115ab2d13)
![image](https://github.com/user-attachments/assets/448b4306-74cf-43c6-a742-487bf1859196)

* **Least and the highest** payments are at the '2' extremes then the further nos. will be in arithmetic mean(AM).

![image](https://github.com/user-attachments/assets/14344b50-5de8-46b1-852f-6662ba2846c6)
![image](https://github.com/user-attachments/assets/d57ce25b-c02a-41e3-9c04-762dca10ad30)
![image](https://github.com/user-attachments/assets/71f093d6-c53a-42f5-ac7b-73aba8bd8b4f)
![image](https://github.com/user-attachments/assets/15e16e16-990d-4a91-9726-ae825a86511a)

* If 'P' got least then 'D' would get the highest but according to the question 'D' did not get the highest payment. So this is **not possible**.

![image](https://github.com/user-attachments/assets/1744d54d-cccc-4bef-88dd-332e3e30f71f)

* If 'P' got least at '2' then 'D' would get the highest at '1' but that is also **not possible** as 'D' did not get the highest payment.

![image](https://github.com/user-attachments/assets/f5835637-11ed-46ea-af0c-00cfe8e8ec75)

* If '2nd' is **least** then '1st' is the **highest**.
* As 'F' got '150k' more than 'R' so 'R' cannot be the **highest**.
* After 'J and F', 'R' comes so 'R' is at the '4th' position.

![image](https://github.com/user-attachments/assets/531840e6-6a96-441f-b582-ec3877f0a6b3)
![image](https://github.com/user-attachments/assets/45a8ff41-018c-48b7-98c2-be570636f2e4)
![image](https://github.com/user-attachments/assets/86e84100-b2f2-4837-baba-8cda8ee925b7)
![image](https://github.com/user-attachments/assets/990044a7-e7b5-4a54-a268-33389577c1b1)

* If we take order from max. to least then '1st' is the max. and '3rd' is the '2nd max or next max' after '1st'.

![image](https://github.com/user-attachments/assets/59c723e8-a07c-4602-96ec-736e42e46870)

* P > 200k.
* If 'F' is at '5th' position.
* 5th - 4th -> 6p + 10r - (4p + 12r) -> 2p - 2r.
* We got, P = 150K.
* This is **not possible** because we know that 'P > 200k' and '150K < 200K'.

![image](https://github.com/user-attachments/assets/ee6e5b2d-7ea6-404f-a215-f781d01ee174)
![image](https://github.com/user-attachments/assets/bacd1017-3f77-4d21-8956-c9233d0238ff)

* 'F' is at '6th' position.
* 'J' is at '5th' position.

![image](https://github.com/user-attachments/assets/3f754ed2-6311-44a6-b1f7-ae14261b7da9)

* According to the order '6th' is **greater than** the '4th' payment.
* '6th' - '4th'.

![image](https://github.com/user-attachments/assets/29214bf7-042d-41e8-99f2-8a250a50b9c6)
![image](https://github.com/user-attachments/assets/5f8e8013-eaf9-44a0-a633-1c92ee024093)
![image](https://github.com/user-attachments/assets/e5011392-7b4d-4645-b6b1-1d418feb17fd)

* Sum -> 3600K + 1200K + 2400K + 1800K + 2100K + 1950K -> 13,050K. [3] [Answer]
* Median Payment -> Write all of the payments in **ascending order**.
* '6' terms -> Even no. of terms.
* Avg. of 3rd and 4th term is the Median Payment. [4] [Answer]

![image](https://github.com/user-attachments/assets/03e66aeb-6bfc-4658-9bae-9be576ede741)

* [Question] [Practice Again] [Tricky Question]

![image](https://github.com/user-attachments/assets/42009947-f519-4d04-932e-44fe1f486324)
![image](https://github.com/user-attachments/assets/f82a6b63-8b67-4056-b09e-3688c2b4033e)

* Attacking Point -> 

![image](https://github.com/user-attachments/assets/300ea2d1-d42b-4938-9a01-6c9a9b9c3782)

* They would be the **same**.
* 'H' cannot be the '4th' because 'H' saw 'YB' when entered but at '4th' it has 'RB' on entry.
* 'H' cannot be the '2nd' because 'H' saw 'GB' on exit but at '2nd' it has 'RB' on exit.

![image](https://github.com/user-attachments/assets/49378aa9-c597-491a-9fd3-ed364a00baa5)
![image](https://github.com/user-attachments/assets/e487ec52-6339-42db-8108-220921025f4f)

* For 'J' there was **no change** when 'J' entered and exited. So '2nd' can't be 'J'.
* When 'P' entered 'B' is adjacent to 'G'. So '2nd' can't be 'P'.

![image](https://github.com/user-attachments/assets/837933ba-d1c5-4f24-85db-3673a76e65ab)
![image](https://github.com/user-attachments/assets/993eef7f-bd2b-47fc-855f-b38b20c566b5)
![image](https://github.com/user-attachments/assets/bb560199-902c-446a-9225-6880fe02def3)
![image](https://github.com/user-attachments/assets/531962da-56c9-4d01-94cd-7ba265f6d4b2)
![image](https://github.com/user-attachments/assets/2ff674c6-6aa0-49b9-af6b-2d5cd4d94665)

* Case **1** -> 'P' at '4th'.
* This is **not possible**.
* 'J' is at '4th'.

![image](https://github.com/user-attachments/assets/41af9d80-bc97-4038-a589-21b5e0587320)
![image](https://github.com/user-attachments/assets/d34077e7-dd55-4d17-ad11-0da58fb082ac)

* Where will 'RB' will lie?

![image](https://github.com/user-attachments/assets/867ae3e5-c5e5-4677-8def-4e8f97829694)

* In 'P', 'B and W' interchange.

![image](https://github.com/user-attachments/assets/e12bd374-b0f8-4ba1-a044-c92fe629e8a6)

'B and W' will interchange.
'G and Y' can interchange.

![image](https://github.com/user-attachments/assets/fd295d22-9564-43cd-9791-f6aede51813e)

* The box is either there or not there. It is either '0' or '1'.

* Blue(B) -> 2/6 + 6 + 5 * 3 -> 23/27.
* 21 + 2 = 23 OR, 21 + 6 = 27
* Pink(P) -> 3 * 5 -> 15.
* White(W) -> 6/2 + 2 * 2 + 6 * 2 -> 18/22.
* 16 + 2 = 18 OR, 16 + 6 = 22
* Green(G) -> More than 15 -> No need to count.

![image](https://github.com/user-attachments/assets/eca3bdfb-7818-4e48-8489-8e47aa60c147)

* Pink. [4] [Answer]

* Max. diff -> Min/minimize - Max/maximize.
* Min/minimize  -> Constantly on the left hand side.
* Max/maximize -> Constantly on the right hand side.
* Yellow(Y) -> 5 * 1 + 4 -> 9.
* Min -> Y = 9.
* Blue(B) -> 3 * 5 + 6 + 6/2 -> 23/27.

![image](https://github.com/user-attachments/assets/ae7cdaec-a753-4baa-865c-39b4b95f0f08)
![image](https://github.com/user-attachments/assets/5dff8213-77d1-41e3-b527-398573e445e5)

* 18. [5] [Answer]

![image](https://github.com/user-attachments/assets/5772e889-11fe-4a08-acb5-27921dd5de6e)

* [Question] [Practice Again] [Tricky Question]

![image](https://github.com/user-attachments/assets/29d2e0ea-c71e-413d-a647-9b3f0868852d)
![image](https://github.com/user-attachments/assets/ebca4805-b0a4-4b22-929e-6644d75965d6)
![image](https://github.com/user-attachments/assets/38721217-4556-402c-ae9b-5ae826498ffa)
![image](https://github.com/user-attachments/assets/cd676fd1-3518-4b6e-ac1b-a1cae8c3f831)

* 'a' min is '0' is **not possible**.

![image](https://github.com/user-attachments/assets/2fb6d67b-f098-42ce-a5cd-fb2b0b3a4636)

* [Concept] [Logic]

![image](https://github.com/user-attachments/assets/b8f723d1-626e-41b4-8f81-ed92cef109b9)
![image](https://github.com/user-attachments/assets/5ee1fbdb-d47b-4fc9-af29-51077b7691a6)

* Price of '1' ticket -> 885.
* If we buy '1' ticket of 'A1' category and to compensate that we need to buy '10' tickets of 'A4' category.
* We need to minimize 'A4' category.
* With purchasing 'A1' category we are not minimizing 'A4' category.
* If we  purchase 'A1' category then we are not minimizing 'A4' category.

![image](https://github.com/user-attachments/assets/b9612d3c-f0a7-4e58-ab9e-3feac719f159)

* We need to minimize 'A4' category.

![image](https://github.com/user-attachments/assets/0a381226-f3cb-4b00-adbb-f2a90b2b4af2)
![image](https://github.com/user-attachments/assets/3f9e62e0-9bc6-4815-8802-e9777e0b02a8)

* If we buy '1' ticket of 'A3' category then we have to buy '1.2' ticket of 'A4' category.
* This is the **good case** for us.
* We don't need to buy 'A1 and A2' tickets.

![image](https://github.com/user-attachments/assets/7de76631-562b-4d6a-b0d6-166f2812f91e)
![image](https://github.com/user-attachments/assets/c243caf9-a61b-4f66-af87-8310c6145f9a)
![image](https://github.com/user-attachments/assets/b98fcfec-74bd-4b85-a40b-42598e82db50)

* We have to use 'A3 and A4'. 'C and D' is '0'. 'A1 and A2' is '0'.

![image](https://github.com/user-attachments/assets/d73a03bc-9ac1-45f4-ab9b-0aae0c6b5689)

* 12C = 0.
* 15D = 0.

![image](https://github.com/user-attachments/assets/937dba79-9d2f-406f-928b-acc9249d45fb)
![image](https://github.com/user-attachments/assets/3968a754-17f6-4402-9942-e30fc5e44801)

* 'a' min = 55. [1] [Answer]

![image](https://github.com/user-attachments/assets/3c12c0da-a81c-46a8-b7da-e62da84c5bdf)
![image](https://github.com/user-attachments/assets/d4e77fad-d762-4592-afc1-36dcdc602703)
![image](https://github.com/user-attachments/assets/6bf2256b-34d9-496d-b906-a15e31841dc8)

* We have to reduce '90000' deficit **quickly**.
* We have to maximize 'A1' category.
* Instead of '2250', they are paying '750'. So we are getting a deficit of '2250 - 750 -> 1500'.
* We have to reduce '60' tickets only.
* Save -> 150 - 60 -> 90.

![image](https://github.com/user-attachments/assets/42765fb4-09e2-4244-b566-16de48e217e8)

* A1 -> 90. [2] [Answer] [Method **1**]

![image](https://github.com/user-attachments/assets/a6007928-776e-44e8-8827-00c9ac27407b)

* A1 -> 90. [2] [Answer] [Method **2**]

![image](https://github.com/user-attachments/assets/ff301745-3b23-4e0e-a6c3-9f39d5d73b56)
![image](https://github.com/user-attachments/assets/cd20f088-e04b-458b-9030-d6c52525214c)

* '67a' has to be a multiple of '3'.
* '67' is not a multiple of '3'.
* 'a' is a multiple of '3'.
* 67a -> 67 * 3 -> 201.
* To minimize 'd', we need to maximize 'k'.
* d = 8. [3] [Answer]

![image](https://github.com/user-attachments/assets/3fe78c37-6a84-44a7-bbf8-fa99c4c9ab9e)
![image](https://github.com/user-attachments/assets/a7b520bb-0a8b-4d6d-b804-12179a2f652a)

* '53a' has to be a multiple of '5'.
* '53' is not a multiple of '5'.
* 'a' has to be a multiple of '5'.
* d = 10. [4] [Answer]

![image](https://github.com/user-attachments/assets/43cd4bf3-d93a-401c-ab31-bf02e99b814a)
![image](https://github.com/user-attachments/assets/3d7fa5e8-3959-4959-a6bc-79c69f22b807)
![image](https://github.com/user-attachments/assets/65b81497-4b2f-4657-be32-59ed6514d812)
![image](https://github.com/user-attachments/assets/288f849d-578e-438a-961f-8b4d774ab583)
![image](https://github.com/user-attachments/assets/ac87e717-ca83-4335-90e9-a26c7db79e15)

* If -> Multiple cases will be formed.
* All of them are multiples of '10'.

![image](https://github.com/user-attachments/assets/7fbe8378-4970-4d6d-a566-4a3512f769a9)

* We cannot have multiple of '25' in cows(C). We will have '35'.

![image](https://github.com/user-attachments/assets/343474f3-17bb-45fd-b59d-06f1e7000196)

* Multiple cases. 
* 145 - 35 -> 110.
* We cannot take '50' as it is a multiple of '25'.

![image](https://github.com/user-attachments/assets/aa60c1a2-5d11-4199-8af6-3b6c74e14b24)
![image](https://github.com/user-attachments/assets/7c595783-0011-46f8-99d0-19df013a1333)
![image](https://github.com/user-attachments/assets/154e5e1d-b5c5-4693-b17c-f00070460f3f)

* 130 - 10 -> 120.
* Goat(G)'s two out of the '3' is same.

![image](https://github.com/user-attachments/assets/8a992aba-8099-4649-bd48-112020d18a26)

* This is not possible.

![image](https://github.com/user-attachments/assets/6dc67029-ec9d-40ee-a2ac-b0a19307607d)

* This is not possible. Buffalo values are all distinct.

![image](https://github.com/user-attachments/assets/0a88ca9a-274e-4b3f-aaf3-40bfbdda9746)
![image](https://github.com/user-attachments/assets/853abba8-8cdc-4135-9b98-6afdbab9e505)
![image](https://github.com/user-attachments/assets/2dbb76d9-207b-4f18-ac5f-0542491810ff)

* 50 + 50 -> 100.
* 60 + 40 -> 100.

![image](https://github.com/user-attachments/assets/20304e1f-64c1-417c-9a28-0f13a04d4160)

* '145 and 130' are fixed.
* '95 and 130' are flexiable.

![image](https://github.com/user-attachments/assets/c62f256c-485e-428a-bfa2-74af9478c18f)

* Case '4' is the replica of case '2'.

![image](https://github.com/user-attachments/assets/9e40666a-3f95-4b2c-8b10-e29e7eab8c58)

* We got '4' cases.

![image](https://github.com/user-attachments/assets/2aba0c5e-536a-4287-906c-2adebb97a130)
![image](https://github.com/user-attachments/assets/d8921076-1d61-41ce-86b3-ace3d1f87b5f)

* Q1 -> Case **3** only.
* 60 + 60 -> 120. [1]  [Answer]

![image](https://github.com/user-attachments/assets/e3422f13-93ab-44c2-98f0-872d88f56546)

* Q2 -> Case **2 and 3** only.
* Case 2 -> 60/40 -> 3/2.
* Case 3 -> 50/60 -> 5/6.
* Option **D**. [2]  [Answer]

![image](https://github.com/user-attachments/assets/38d7bf27-4f51-4cb7-90e3-b9a08f41f1cb)

* Hen(H) -> H1 = 2, H2 = 5, H3 = 4 -> 2 + 5 + 4 -> 11.

![image](https://github.com/user-attachments/assets/21c91de7-00d2-4190-a3ea-2fc752b015cc)
![image](https://github.com/user-attachments/assets/6be10fd2-f80b-4f50-81f4-21f0cccc9bcc)
![image](https://github.com/user-attachments/assets/865136bb-831f-410a-b489-2c88a3606fa1)
![image](https://github.com/user-attachments/assets/3f7faae4-9c5a-4377-a865-7db73f7631ab)

* In every case we are getting '11'. [3] 
 [Answer]

![image](https://github.com/user-attachments/assets/05b9fab1-e26d-4fd7-9ad4-b59ed05cf797)

* In case **2**, we are getting '7:5' for statement '1'. So statement '1' can be True.
* In none of the cases, we are getting '5:4' for statement '2'. So statement '2' cannot be True.
* In none of the cases, we are getting '2:1' for statement '3'. So statement '3' cannot be True.
* In case **1**, we are getting '6:5' for statement '4'. So statement '4' can be True.
* Option **2**. [4] [Answer] 

![image](https://github.com/user-attachments/assets/90ccdb97-bb41-4de1-a784-2ad0d64143a1)

* In case **3**, goats in 'H1' is '25' and in 'H2' is '50' which is twice.
* No. of buffaloes(B) -> 60 -> option **C**. [5] [Answer] 

![image](https://github.com/user-attachments/assets/e590cb91-706b-4609-9dc8-0cc2c7d790b2)
![image](https://github.com/user-attachments/assets/2e3153f2-a075-41a8-8966-fcbc9e153c69)
![image](https://github.com/user-attachments/assets/7c02d0c2-bbb0-48c5-8a61-71b8b291bc1e)
![image](https://github.com/user-attachments/assets/f22c2fa0-4f41-41e5-99ec-6cd86697fbad)
![image](https://github.com/user-attachments/assets/b7bab639-1bcd-4a3e-ad66-172a9a87da1d)
![image](https://github.com/user-attachments/assets/06221203-4de3-4c01-8985-7d47b9f8446a)

* A huge no. of cases we are getting. We will solve them by looking at the questions. 

![image](https://github.com/user-attachments/assets/b245a84f-1297-4951-8ba0-ecb3b0648199)
![image](https://github.com/user-attachments/assets/1e75b685-24c8-4bc3-90e0-50797b2ddc31)
![image](https://github.com/user-attachments/assets/1d55e73f-7196-4b68-b3af-77c3a903dddb)
![image](https://github.com/user-attachments/assets/26128d5f-f2dc-4080-a0c3-262b53a0d240)

* No cases are possible further.
* Cases -> 1 + 2 + 2 + 1 -> 6. [1] [Answer] 

![image](https://github.com/user-attachments/assets/88a6817e-cf8a-4dba-95bc-f136d4712ef7)

* 10c and 2a -> Always even -> 2b also always even then.
* '0' is not possible. We cannot have '0'.
* 'b' is always even.

![image](https://github.com/user-attachments/assets/552571fb-f2a9-4cb4-8bd9-35cfcf280583)

* 16 > 12 -> Not possible.
* 12 > 12  -> Not possible.

![image](https://github.com/user-attachments/assets/f072fdad-ad8b-402f-a0dd-de71c4a034e0)
![image](https://github.com/user-attachments/assets/62057c0b-48ac-4aae-8c47-99a2d996e59f)
![image](https://github.com/user-attachments/assets/487f3e5a-5dbd-4fd6-9b78-bc7ac68c3f86)
![image](https://github.com/user-attachments/assets/8a494fe8-e4e9-4c7b-a599-b22ef7ac86c2)
![image](https://github.com/user-attachments/assets/2c71669e-1acb-4770-a583-011639b90c5d)

* We need 'a, b, c' atleast one or once(1).
* No cases are possible further.
* 1 + 2 + 1 + 1 -> 5. [2] [Answer] 

![image](https://github.com/user-attachments/assets/d6ba15d0-2c83-4d2e-a708-92312c6e1e20)

* [3] [Answer]
* In Q1, we saw that the min. value of 'C' is '7'. 'C' cannot be less than '7'. 

![image](https://github.com/user-attachments/assets/136f49ae-9eed-422e-82b3-a5a338955c87)

* 100days -> 100 * 100 -> 10000

![image](https://github.com/user-attachments/assets/498b25e8-617c-45e0-9349-1ed08a28c8c1)
![image](https://github.com/user-attachments/assets/ec05a1ea-a205-4e80-a276-3099f9b3bc16)

* '7' expert workers are required to build a palace.
* [3] [Answer]

* a = 0, b >= 1, c >= 1.

![image](https://github.com/user-attachments/assets/79477f02-dcae-4576-816b-92ead598308a)
![image](https://github.com/user-attachments/assets/b12e62c1-b984-4a82-afbc-006e4afb5efa)
![image](https://github.com/user-attachments/assets/2dc695dc-a508-4ee8-9ff1-d45b9799bcc0)

* This is only possible when 'C = 0'.
* Nothing is possible. No cases are possible.

![image](https://github.com/user-attachments/assets/55145413-9e73-4433-931f-818f3db5a6ca)
![image](https://github.com/user-attachments/assets/48a93ea4-c407-4265-8c9f-722f38e6b00c)
![image](https://github.com/user-attachments/assets/d3478737-ebf8-43a6-8521-d1606ffe7404)

* We are getting 'C = 0' but in the question it is mentioned that 'C >= 1' atleast. No cases for 'N' are possible.
* N = 0. [4] [Answer]

![image](https://github.com/user-attachments/assets/3b802e70-b9b7-40c5-bc5f-225f6fe92218)
![image](https://github.com/user-attachments/assets/b98b4559-36e3-48ed-8730-b7c255316b83)
![image](https://github.com/user-attachments/assets/61922525-ff0d-4dc5-8405-d190bdf510c5)
![image](https://github.com/user-attachments/assets/062d642f-c34a-47c1-b195-f5986e6ae334)
![image](https://github.com/user-attachments/assets/265df7b1-a02d-4dbf-9e96-bb0b1cc712e0)
![image](https://github.com/user-attachments/assets/a42b9b94-8bd0-4010-be1f-e3d60533a1bf)

* The kids entering at '7 or 8AM' have to stay for atleast '2hrs' so nobody leaves at '7 or 8AM'. 

![image](https://github.com/user-attachments/assets/b9720164-c3e6-4b9e-9079-8ce550d763e8)
![image](https://github.com/user-attachments/assets/b91b56af-47ef-4de1-b38d-7d174d737453)
![image](https://github.com/user-attachments/assets/a9cfee21-6824-46d3-9d77-d19c8b7ad0eb)
![image](https://github.com/user-attachments/assets/187a023f-63d3-493b-9df2-b6a6f75dbc3a)
![image](https://github.com/user-attachments/assets/3d87e506-397d-4746-841e-d117eb46a7f0)

* '2PM' exist cannot be '1' only, it will be '1 + something'.
* Total is '10', we got '9' already, so the '2PM' exist is left with '1' only.

![image](https://github.com/user-attachments/assets/46be0b16-d4ce-48f0-8554-231847e6043a)
![image](https://github.com/user-attachments/assets/41bf500b-1d41-416a-a991-7b037ce4ae68)
![image](https://github.com/user-attachments/assets/0c443846-dcda-4352-9784-51a8557ee950)
![image](https://github.com/user-attachments/assets/ec3faa46-d24d-49af-9a7a-d25f220ae912)

* Answer -> 4. [1] [Answer]
* Answer -> 1. [5] [Answer]

![image](https://github.com/user-attachments/assets/0ef2f226-bee8-4db5-a27e-00c7b0c2c972)
![image](https://github.com/user-attachments/assets/4408a935-ed3d-44ee-b19e-01810dd4c1e2)
![image](https://github.com/user-attachments/assets/5676b769-3341-4c14-87f4-d232bee11d2f)

* 20 - (1 + 8 + 2) -> 20 - 11 -> 9 left.

![image](https://github.com/user-attachments/assets/97ff9c42-eb82-404b-89c2-9540f8c998fb)
![image](https://github.com/user-attachments/assets/62e321b4-62d3-43c3-8b56-f544f6be2d26)

* Answer -> 9. [4] [Answer]

![image](https://github.com/user-attachments/assets/14bc481e-c0de-45e6-964c-e610d3ad89c5)
![image](https://github.com/user-attachments/assets/2a72f2d4-4d51-4e85-b430-c9c07fd456e0)

* 2x + y + 2 + 1 = 20
* 2x + y = 17.

![image](https://github.com/user-attachments/assets/a90f5652-20c1-4254-ae94-0de45f0dc203)
![image](https://github.com/user-attachments/assets/fbe783d8-ae09-4735-b509-c064ebd8fd90)

* 'y' min is '1'.

![image](https://github.com/user-attachments/assets/548640be-1cf7-4f4d-878e-375c3bb03359)

* 2x = 9
* 'x' min is '4.5' 
* 'x' min is '5'. 

![image](https://github.com/user-attachments/assets/b1c64538-59fc-4812-ab02-4224f2187e56)
![image](https://github.com/user-attachments/assets/bc0a26bc-c570-4467-bfb6-dab98016fe06)
![image](https://github.com/user-attachments/assets/b9ca1403-b3fe-4675-ae3c-fe21c54e709c)

* 'y' max is '7'.

![image](https://github.com/user-attachments/assets/34b0addf-abe4-4d54-bcc7-93934ef69ea8)
![image](https://github.com/user-attachments/assets/18b280a5-7e0d-4bc3-9b6d-a7ab9e0d0c29)
![image](https://github.com/user-attachments/assets/78b28b1b-40ea-4704-8f33-14f30fcca4cc)
![image](https://github.com/user-attachments/assets/93e5309e-3124-4dc6-a565-3ebf2f21e44e)
![image](https://github.com/user-attachments/assets/ed5dbe36-f956-4fc9-a785-9d49f85b125f)
![image](https://github.com/user-attachments/assets/f91e0b28-5dce-40ac-bc55-5429d233bd9e)

* Point '3' -> Review/later use.
* Point '5' -> Review/later use.

![image](https://github.com/user-attachments/assets/bc59b3ab-31fc-44e7-a91c-332ad62b11be)

* Point '6' -> We have to repeately come to this point.

![image](https://github.com/user-attachments/assets/f1488406-22eb-4b41-a228-96614ce48639)

* If we take pathology in section 'III' from '9-10'.
* We will have pathology in section 'II' from '8-9'.

![image](https://github.com/user-attachments/assets/bcab4d94-707c-46d4-b001-8b32e3418f23)

* This is not possible.
* We have pharma in section 'III' from '9-10'.

![image](https://github.com/user-attachments/assets/446184bc-d074-4bdb-b905-4493f54dcc6b)
![image](https://github.com/user-attachments/assets/48a8497e-09c9-418c-a190-66d25dbd77e2)

* In whichever columns, 'FMT' is there, we canoot put a new 'FMT' in that column.
* We cannot have pathology in section 'III' from '8-9'. According to point '5'. 
* Micro biology is there in section 'III' from '8-9'.

![image](https://github.com/user-attachments/assets/03226b00-a467-4ac9-a2b2-415d2111421d)
![image](https://github.com/user-attachments/assets/195b49a7-6b06-4e42-9593-3ec8eb7aaa75)
![image](https://github.com/user-attachments/assets/525788fe-b144-49b6-9da3-e9d7a69058d5)
![image](https://github.com/user-attachments/assets/4b6330f7-905a-4862-bca7-53f85b1b2ad4)

* Whether micro-biology is in section 'II' of '9-10' or '10-11', we are guranteed to have micro-biology in section 'I' of '11-12'.

![image](https://github.com/user-attachments/assets/7b1c2f68-1c59-4fe7-82f5-c699a2792fc2)
![image](https://github.com/user-attachments/assets/32716f01-d851-4dbd-b375-353ad5be9d34)
![image](https://github.com/user-attachments/assets/c76d522f-4b0c-4ef6-abf9-35c56907c0a2)

* Patho and micro are coming together.
* We already have a micro in section 'I' of '11-12', that's why micro cannot come in section 'III' or section 'IV' of '11-12'.
* That's why it is coming in section 'IV' of '12-1'.

![image](https://github.com/user-attachments/assets/e58d7658-d822-4497-801a-00ea4d79eee6)
![image](https://github.com/user-attachments/assets/9f66836e-32df-47df-a99c-46b8af0241f8)

* 'CM' is already in the row of section 'II'.
* 'Pharma' is in section 'II' of '12-1'. 
* 'CM' is in section 'V' of '12-1'. 

![image](https://github.com/user-attachments/assets/30cf2178-5e81-4c66-ba6c-e6491f7368bc)
![image](https://github.com/user-attachments/assets/19619423-ce4d-455e-9a01-59534cf926df)
![image](https://github.com/user-attachments/assets/eb6ebed3-ee87-41ed-b36e-68709886db2a)
![image](https://github.com/user-attachments/assets/acd48d95-3b2e-44a4-952b-d442a3e52d62)
![image](https://github.com/user-attachments/assets/bc671a79-c361-474a-af11-6024e01e2219)
![image](https://github.com/user-attachments/assets/80a095b0-c925-42e3-9b91-9b440d312b14)
![image](https://github.com/user-attachments/assets/3f2c154d-3f14-49e0-bf85-bb15b1dbf3f8)
![image](https://github.com/user-attachments/assets/a59362b8-e09a-4208-95a5-146447752663)

* [**VERY IMPORTANT**] [Practice Agin]

![image](https://github.com/user-attachments/assets/87df2ce4-5b7e-4dbb-af5e-89eed8efe597)
![image](https://github.com/user-attachments/assets/fbaa7828-84b1-4aa2-8048-d7148a4d70a9)
![image](https://github.com/user-attachments/assets/553a6120-5c7f-4711-8d70-2b7f3aba6df6)
![image](https://github.com/user-attachments/assets/cffdec60-44a8-4f9b-a9b2-4c1c3f9e28a0)
![image](https://github.com/user-attachments/assets/3f69d6bf-0ede-4582-80e8-1022fad7e681)

* Only '1' case is possible.

![image](https://github.com/user-attachments/assets/37e0bc7c-e3db-4e1f-8d43-8ba91d6079b7)
![image](https://github.com/user-attachments/assets/ffae0ab3-402e-4f39-851f-f9e8a0aa71fc)

* In avg. marks, 'B' has rank '1' and 'A' has rank '2'. So avg of 'B' will be more than avg of 'A'.
* All are integer values.
* Total marks of 'D' is more than the total marks of 'B'.

![image](https://github.com/user-attachments/assets/c3d6cd00-fb50-4fa4-9d92-c7b530e2aa04)
![image](https://github.com/user-attachments/assets/838d1b55-7a95-4ad8-b5ad-45561d018ab8)
![image](https://github.com/user-attachments/assets/b8bbf8ea-da4c-4da8-bcaf-07cfc82ba422)
![image](https://github.com/user-attachments/assets/37dd434e-d864-4ee0-98bc-c106dfcec659)
![image](https://github.com/user-attachments/assets/d3e8426d-fdb3-4a42-b1c4-7318d62e691e)

* [Answers]
* Discussion in next class.

![image](https://github.com/user-attachments/assets/78c4914c-1c9b-4ce9-828e-0110a3457cc4)

* Next class.

![image](https://github.com/user-attachments/assets/087087e2-f830-48bf-a89f-7ee90f2a91b3)
![image](https://github.com/user-attachments/assets/2381c725-5bc4-473b-b007-11ef95fd2a44)

* Sum = Avg * n. [n -> count/number]
* The nos. are given in **integers**. 

![image](https://github.com/user-attachments/assets/5322f171-5661-41f4-b8c3-d0a54f8a1233)
![image](https://github.com/user-attachments/assets/43875c31-1753-4e68-bb33-6bf2b0144eae)

* Previous class solved. [1] [Answer]

![image](https://github.com/user-attachments/assets/68853d33-ae0e-42e6-b65f-949d06db95e2)

* Avg marks of 'B' is greater than the avg marks of 'C'.
* Total marks of 'B' is greater than the total marks of 'C'.
* The avg marks of each group is alteast '50'. Max. marks is '100'. Mentioned in the question.
* 'b and c' are integers.
* 100 + 25c -> Should be a complete multiple of '24' as they are all integers.

![image](https://github.com/user-attachments/assets/35e33929-b013-4be5-9f6b-b133359fafa5)
![image](https://github.com/user-attachments/assets/e52f063c-762a-4eb2-8b4b-e24e3c890cba)

* 50 <= C <= 100.

![image](https://github.com/user-attachments/assets/6376ac51-85b9-4715-a7c6-346083c7663f)

* We got '2' values for 'c'.

![image](https://github.com/user-attachments/assets/691b797b-67b1-47ea-bdd6-af1a58fca9b4)

* Answer -> 7 or 8. [2] [Answer]

![image](https://github.com/user-attachments/assets/d009ecf1-9635-467e-a368-6d4cf42c173d)
![image](https://github.com/user-attachments/assets/be59ad51-174e-4106-966c-69c9c21ef506)
![image](https://github.com/user-attachments/assets/3593d6da-b4f1-4f1b-91d8-d2c504cb10a5)
![image](https://github.com/user-attachments/assets/7537c8b9-5655-4d91-9763-42989f2e734d)
![image](https://github.com/user-attachments/assets/9361d0ca-ab3a-4f67-bb37-4d27a2074b46)

* '4' possibilities are possible.
* Answer -> 4. [3] [Answer]

![image](https://github.com/user-attachments/assets/ff2b9d57-5fe9-40a6-9a21-aa3b925cafec)
![image](https://github.com/user-attachments/assets/cf66bc50-b85c-43e4-a624-b39039854062)
![image](https://github.com/user-attachments/assets/661b95bf-86bd-4bcf-8b16-a8c7929971f0)
![image](https://github.com/user-attachments/assets/ec59ab6f-d7cc-41ae-af05-1644e78a799d)

* Total marks of 'D' is greater than 'b and c'.
* 600 * 3 -> 1800.
* Avg. marks of 'B' is greater than 'C'.
* 'B' avg. has to be greater than 'C'.
* Diff. between 'b and c' cannot be '0'.
* Min. diff -> 1. [4] [Answer]

![image](https://github.com/user-attachments/assets/9e9488b4-3597-41f4-976e-f85cc5d5985e)
![image](https://github.com/user-attachments/assets/6f88397a-0372-4349-ab10-395dab151067)
![image](https://github.com/user-attachments/assets/b96c9899-30b9-47b6-a43d-b31f007c7e49)

* Find the order of 'A, B, C, D' first.
* The order we want -> A, B, C, D -> 2, 1, 3, 4.
* Remove the options which are not in that **order** -> option **A**.
* Opttion **B**. [5] [Answer]

![image](https://github.com/user-attachments/assets/ba323aee-cbfe-40f5-8152-4ac0b06be4c4)
![image](https://github.com/user-attachments/assets/966f20a9-6fe5-4e6f-9878-8297d4b41da2)
![image](https://github.com/user-attachments/assets/d6682857-2b49-48e4-b5f4-7ee61fad328f)

* Done earlier. [1]























![image](https://github.com/user-attachments/assets/864b7daa-1753-43ec-a4bc-eb52a176cd22)
![image](https://github.com/user-attachments/assets/ed2ac207-a354-41a6-ae4e-4389b0ec6994)
![image](https://github.com/user-attachments/assets/f030e645-e58b-4b12-b929-12ae988b78d6)
![image](https://github.com/user-attachments/assets/718bef38-0572-408d-813b-09ebc929fc29)

* [Answer]

![image](https://github.com/user-attachments/assets/e3997ae6-d5be-4a57-8162-98127d729154)
![image](https://github.com/user-attachments/assets/faea32ae-bc1a-4ad4-a756-5e3339dbe17c)
![image](https://github.com/user-attachments/assets/4717aeb5-b5ab-4053-b52a-d5b3db469e90)
![image](https://github.com/user-attachments/assets/1b9b91cf-ffc9-41a8-8bf5-cd0328829348)

* B -> '3' possibiities.

![image](https://github.com/user-attachments/assets/76b71323-08b7-43e9-a28a-b772cb577684)
![image](https://github.com/user-attachments/assets/f4a6f264-6e13-405d-8754-1dc8e704c0f1)
![image](https://github.com/user-attachments/assets/cec423b9-8b0d-4ff9-ac93-b5ddccc84962)
![image](https://github.com/user-attachments/assets/8c04de71-722d-4304-8693-63661518bdfd)
![image](https://github.com/user-attachments/assets/a99c2d95-8a68-416a-b246-377f65f33ba2)
![image](https://github.com/user-attachments/assets/f8181cdc-5cd2-4fa9-be47-1f90c1198e02)
![image](https://github.com/user-attachments/assets/de03c607-e495-454c-86c4-dc24e41a5d7a)

* Total -> 2 + 2 + 4 * 1 -> 8. [1] [Answer]

![image](https://github.com/user-attachments/assets/8f480dde-3b2a-4cb5-a63f-6adeedd453f3)
![image](https://github.com/user-attachments/assets/0de159d0-072b-4524-997f-7173d6e7cabf)
![image](https://github.com/user-attachments/assets/b4b5c985-09c6-45de-88da-5442adaab4a6)
![image](https://github.com/user-attachments/assets/566d7dac-18a2-4e83-b020-d18c52fe0487)
![image](https://github.com/user-attachments/assets/e547cbc7-5924-4847-a3e2-97a6136839eb)
![image](https://github.com/user-attachments/assets/19766b45-bb4d-4f87-987f-65e875041afa)

* Divya -> Section 'C'. [2] [Answer]

![image](https://github.com/user-attachments/assets/bdaaeabb-6034-4a6a-bec4-aaca5f137e95)
![image](https://github.com/user-attachments/assets/07de81b2-c685-4d0d-95a9-01f040df9d9b)
![image](https://github.com/user-attachments/assets/adbef356-a0b6-41be-8c16-9cddad1b16b3)
![image](https://github.com/user-attachments/assets/9d97c101-9a94-458a-9e9e-624bb8e55fde)
![image](https://github.com/user-attachments/assets/7236092d-d84e-4794-88ce-b45fd77ea7a9)

* Chandni -> Section 'C'. [3] [Answer]

![image](https://github.com/user-attachments/assets/2e985e97-974d-4ce5-99d6-e72db85aedd8)
![image](https://github.com/user-attachments/assets/8fe84126-2789-4e47-982b-726c73a7e92c)
![image](https://github.com/user-attachments/assets/b5973feb-1f54-4431-8a7d-f1b4c54ce25d)
![image](https://github.com/user-attachments/assets/af67d07a-b855-4533-9730-978735e1f718)
![image](https://github.com/user-attachments/assets/5ea36a4c-ef70-46fa-a934-4dba8f8567e9)

* Option **D** -> CBD. [4] [Answer]

![image](https://github.com/user-attachments/assets/43905234-3b45-48ed-b254-170aa3907d20)
![image](https://github.com/user-attachments/assets/61d37076-b9df-441d-99bc-7f7b53f76a61)
![image](https://github.com/user-attachments/assets/2e67f1ff-5150-43c6-b84a-12b61fd30cfe)
![image](https://github.com/user-attachments/assets/32daa3e0-3b75-4a33-8473-9277af84f4e0)

* [Question]

![image](https://github.com/user-attachments/assets/e54b02f9-8946-454c-a5de-e9fe632005de)
![image](https://github.com/user-attachments/assets/9b7ec2a7-9d92-45d9-b485-51848a745de9)

* 4 * 3 + 4 * 1 -> 12 + 4 -> 16.

![image](https://github.com/user-attachments/assets/62df51d6-782a-490f-9302-5df7cf33c78a)
![image](https://github.com/user-attachments/assets/aa2e8be6-398e-4446-8f5b-92ba9badb0fa)
![image](https://github.com/user-attachments/assets/06d8d817-cf0b-4565-9aba-6b41dd342fd4)

* 'S and L' cannot be part of teams 'C and D' i.e '3rd and 4th' teams.
* 'D' is not in team 'C' and 'I' is not in team 'D' but 'D, H and I' are in teams 'C or D'.
* 'D' is not in team 'C' so 'I' is in team 'C'.

![image](https://github.com/user-attachments/assets/98fb1a2a-9d02-419d-acc3-c1fc5f987472)

* 'I' is not in team 'D' so 'Dave' is in team 'D'.

![image](https://github.com/user-attachments/assets/a7e64148-0b49-4acd-9fb4-52008e183b76)
![image](https://github.com/user-attachments/assets/e107a83b-6046-4754-a6f2-016e1deb657f)
![image](https://github.com/user-attachments/assets/dd833404-1838-4283-a1f4-ffd23ba18a8c)
![image](https://github.com/user-attachments/assets/7a524862-578a-4257-a6e5-23f371591872)
![image](https://github.com/user-attachments/assets/a74ddbf4-5f03-41c6-a835-4731da0ad48d)

* [1] [Answer]

![image](https://github.com/user-attachments/assets/4a20429c-3c4c-46ea-980f-c157f81553b7)
![image](https://github.com/user-attachments/assets/cad77d40-f63e-49c3-9be6-a8b5c32cfff6)
![image](https://github.com/user-attachments/assets/0575c6f1-0e76-45d7-8f3c-38cf5c9781df)

* Example.
* Possibility based questions.
* Best possible cases.

![image](https://github.com/user-attachments/assets/fa113ac6-21f7-4dde-b322-85f3cf1eb6f3)
![image](https://github.com/user-attachments/assets/2cb4e60c-0420-49c2-b574-cb43541545bb)
![image](https://github.com/user-attachments/assets/0829c157-f2c7-4240-89fb-22ba755a0548)

* [2] [Answer]

![image](https://github.com/user-attachments/assets/896d901b-fc2a-4c3a-bb6d-08134a44c485)
![image](https://github.com/user-attachments/assets/16b80e18-c203-4788-a6cb-f98c07cb5506)

* 'T and P' have to be in the **same** team.
* [3] [Answer]

![image](https://github.com/user-attachments/assets/22495618-c6f8-403c-b64a-c004d2a00cdb)
![image](https://github.com/user-attachments/assets/efedac04-ab9c-45aa-b4f4-5e39f0e09373)

* [4] [Answer]

![image](https://github.com/user-attachments/assets/d52faffb-fe8a-4fab-95c8-664bb826705c)
![image](https://github.com/user-attachments/assets/c993987f-9e96-4b61-9b25-e496e5ad94ee)
![image](https://github.com/user-attachments/assets/3c7e81d9-66b4-495f-b672-2d39b1625e4e)

* Attacking point -> Minimum and Maximum.
* We will do **Maximum** here so that we will get min. no. of cases as possible. [Logic]

![image](https://github.com/user-attachments/assets/30cb02d6-a4f2-40f0-942c-0482eed87eb2)

* Saeed -> 17 -> 9 + 8 -> 9 * 7 + 8 * 3 -> 63 + 24 -> 87.

![image](https://github.com/user-attachments/assets/3edcb8fa-256d-4a17-bbe2-01413f8eb9b4)
![image](https://github.com/user-attachments/assets/9dc249be-a7cb-4d7a-b8eb-037eee9cd594)

* Shahid -> 13 -> 6 + 7 -> 7 * 5 + 6 * 7 -> 77.
* If we take '7 * 9 -> 63' then '77 - 63 -> 14'. We cannot get '14' via '6'. So this is not possible.
* If we take '7 * 5 -> 35' then '77 - 35 -> 42'. We can get '42' via '6'. '6 * 7 -> 42'. So this is possible.

![image](https://github.com/user-attachments/assets/1707e7d5-e5d9-4b9c-af16-cacad3a238d0)

* 88 - (7 * 5) -> 88 - 35 -> 53 -> Not a multiple of '5'.

![image](https://github.com/user-attachments/assets/18149b84-533a-4b62-bd59-2f52632e1fef)

* For '11' we have '2' possibilities.
* 75 - (7 * 5) -> 40 -> 4 * 10 -> We don't have '10', so this is not possible.

![image](https://github.com/user-attachments/assets/1b3bb778-812c-4ac3-82c7-beeaa2a5dee1)
![image](https://github.com/user-attachments/assets/f98c5fb6-2a18-448a-8d02-666f3f451e2c)

* 10 -> 5 + 5.
* 68 -> Not a multiple of '5' -> So '5 + 5' is not possible.

![image](https://github.com/user-attachments/assets/de5c64e1-fae1-4d2e-9a07-d33ac93e2bb8)

* 67 - (5 * 9) -> 22 -> Not a multiple of '4', so this is not possible.
* So with '5' we will take '11'.  

![image](https://github.com/user-attachments/assets/dd61e76e-4e24-4bf9-857f-5f2a8d75534a)

* For '4'.

![image](https://github.com/user-attachments/assets/fb85ff52-a509-4997-89ed-57c2cf006659)
![image](https://github.com/user-attachments/assets/bb0f1113-5b6c-4b2e-a3e8-551fdb656cb4)

* For '8'.

![image](https://github.com/user-attachments/assets/15bd2b9b-6e4e-48df-ad2a-c35fd2fcaa8b)

* For both '7s'.

![image](https://github.com/user-attachments/assets/b9dc2b5a-6b1c-4c22-866a-8edcb803e838)

* Shop '2' least -> 5 -> 5 * 5 -> 25 -> '5 * 5' combo is with 'smith'. [1] [Answer]

![image](https://github.com/user-attachments/assets/a65e61c3-35b8-4bf7-b895-0db8ec432170)
![image](https://github.com/user-attachments/assets/27295deb-d349-491e-b1e1-05efc85dd091)
![image](https://github.com/user-attachments/assets/43d60c32-c1b2-4b32-a11c-1d2002980e4a)
![image](https://github.com/user-attachments/assets/28497a5d-13b9-471a-bae6-b5fef46aead1)
![image](https://github.com/user-attachments/assets/39cfc933-d43e-4269-bdb3-35c0775fef23)

* [2] [Answer]

![image](https://github.com/user-attachments/assets/bee03134-cd52-4296-849d-bae0f65ebf2b)
![image](https://github.com/user-attachments/assets/4aa990db-7b3c-4ccb-abe2-4634aaeb866a)

* Sachin, Shane, Shahid -> 3. [3] [Answer]

![image](https://github.com/user-attachments/assets/1c02f88a-d6fe-4f29-8d24-fc7d17569240)

* Sachin-Smith, Schwag-Saqlain -> 2. [4] [Answer]
* Sachin -> S2, S5
* Schwag -> S3, S4
* Steve -> S4, S1
* Shane -> S2, S4
* Sanath -> S3, S5
* Saeed -> S5, S3
* Saurav -> S5, S1
* Smith -> S5, S2
* Shahid -> S2, S1
* Saqlain -> S4, S3

![image](https://github.com/user-attachments/assets/d4ba14a6-28c4-498e-92bc-646ffbaa1316)
![image](https://github.com/user-attachments/assets/4f51ee23-d324-43d8-8a73-68c723022bd9)
![image](https://github.com/user-attachments/assets/c5f99859-ceea-44fa-a03f-c25c5cb177f3)
![image](https://github.com/user-attachments/assets/35d9e257-5d48-487a-89c6-46fa16c9d72e)

* [Question]

![image](https://github.com/user-attachments/assets/4aff1634-fa8e-453b-a225-92d881a36ad6)

* Attacking point -> Overlap/Common between points.

![image](https://github.com/user-attachments/assets/f46f896b-ec37-4ecf-9595-56cbe95de655)
![image](https://github.com/user-attachments/assets/0a1006be-578f-4afe-90e1-c0e1c99e98e5)

* Heaviest -> 1st.

![image](https://github.com/user-attachments/assets/ef3e5e65-2150-4c22-a363-1b3e2da27c17)

* We getting '2' options/possibilities. If Heaviest is at '1' then 'K' is at '6th'. If Heaviest is at '2' then 'K' is at '7th'.
* Case '1' is gone.

![image](https://github.com/user-attachments/assets/a084fd52-1d46-4e57-ad1e-d31fb6e5fe17)
![image](https://github.com/user-attachments/assets/3cdf0d53-19b4-407f-86e2-fce5c6af4f8f)

* 'P' can come only at '1st or 2nd' position. We getting '2' options/possibilities.

![image](https://github.com/user-attachments/assets/8bddadfb-64ac-488f-aec3-62943a395ea7)
![image](https://github.com/user-attachments/assets/d5155f9e-6625-49ba-8dcf-0456fdd4dbfe)
![image](https://github.com/user-attachments/assets/8d8f9945-8546-4934-84f2-948c2215020d)

* Case '3' is gone. We cannot put 'R' in case '3'.

![image](https://github.com/user-attachments/assets/e8ba4b4b-ac19-4181-925c-7b325e55a409)
![image](https://github.com/user-attachments/assets/b46d98e2-4383-4333-bbbf-b3b5ddd0516c)
![image](https://github.com/user-attachments/assets/6462d780-74f6-48de-a256-58e20b4b7a5f)

* Answer -> 3. [3] [Answer]

![image](https://github.com/user-attachments/assets/134c5a54-4714-4956-83cb-ffff011bb401)

* G -> 3rd heaviest -> 3rd position. [4] [Answer]

![image](https://github.com/user-attachments/assets/02f32e14-0dec-49a7-87ad-82aad118dcc6)

* 3. [1] [Answer]
* Pavan(P) -> Option **A**. [2] [Answer]

![image](https://github.com/user-attachments/assets/2aae0376-deed-4521-8706-56f8a3e868bf)
![image](https://github.com/user-attachments/assets/5bee6fc1-b08a-4b6d-b802-f4f05fc6bb1d)
![image](https://github.com/user-attachments/assets/1ad77be9-68ba-4148-93b8-5c2be80db1b6)

* Unconventional Graph or Candle-Stick Graph -> Convert it into **normal table** format. [Logic] [Concept]
* Gray Rectangle -> 1st match scored more than the last match.
* White Rectangle -> Opposite of **Gray Rectangle** -> 1st match scored less than that of last match.

![image](https://github.com/user-attachments/assets/945d3026-55cc-4117-ad50-d61ebb820f40)
![image](https://github.com/user-attachments/assets/cb3aedbd-555e-489e-9863-f73c5042674a)
![image](https://github.com/user-attachments/assets/24639dfe-5583-4211-b949-6348dde4b40f)

* NA -> Not Applicable.

![image](https://github.com/user-attachments/assets/6ac08bea-f94c-45ed-a718-6fd063936eb7)
![image](https://github.com/user-attachments/assets/40eb1d4a-8b8a-40c5-9083-8875f2a4a37d)
![image](https://github.com/user-attachments/assets/9c7b11fd-4e17-43b1-a1aa-58027557e613)

* The line in **Gharma** goes till the end of the candle. [Logic] [Concept]

![image](https://github.com/user-attachments/assets/b454a06d-cc18-4be2-a47d-0f784446ca38)
![image](https://github.com/user-attachments/assets/c45d1353-cff3-4cd1-9957-4db6465b648f)
![image](https://github.com/user-attachments/assets/a5173bdf-4b7d-43dc-8b14-a20e20f1cd95)
![image](https://github.com/user-attachments/assets/837deb09-48ff-4dcd-aa79-49b1fa1b2e2a)
![image](https://github.com/user-attachments/assets/435f3c81-1fb9-4906-8879-d7fea45ac402)
![image](https://github.com/user-attachments/assets/1defb9aa-6907-4f62-8b3b-0ef64aea6582)
![image](https://github.com/user-attachments/assets/fc9f76e8-930e-4da4-a534-cab1c98d8ca5)

* All of these '6' scores are not possible.
* 0 to 65 -> 66.
* Left -> 66 - 6 -> 60.

![image](https://github.com/user-attachments/assets/30150c38-efab-4c6b-a436-d11b0f448a72)

* Sum -> 17 + 12 + 13 + 18 -> 60.
* Max score -> 65.
* Min score -> 0.
* Attacking point -> Maximum/minimum.

![image](https://github.com/user-attachments/assets/593b7f17-101d-4691-b675-17636cb741db)

* Except Gahul, all of their max. score is '55'. So, Gahul can have any value more than '55'.

![image](https://github.com/user-attachments/assets/af96b8ae-182e-44dd-9e78-f8ce20266123)
![image](https://github.com/user-attachments/assets/27611977-1c6a-4f4c-96af-3ca7b488a147)

* Gahul's lowest is '0' and all of their min. score is '5'.
* He scored '50', so add '50' also.

![image](https://github.com/user-attachments/assets/962297d2-c22d-41f0-b47f-5537492f9179)
![image](https://github.com/user-attachments/assets/4bde3d98-891c-469a-a7a6-e68b837cf7a1)
![image](https://github.com/user-attachments/assets/0fb79263-a370-42a3-94d4-de9838c02c38)
![image](https://github.com/user-attachments/assets/8537dbd1-22c9-4a95-8739-b5457a853e78)
![image](https://github.com/user-attachments/assets/e9bd6a96-d3fe-4046-a2be-34a1084a509c)

* The prime nos. after '40' cannot be given to 'Goli or Gharma'. They are given to 'Gahul'.
* The prime nos. after '30' are given to 'Gharma'.

![image](https://github.com/user-attachments/assets/c853d92a-6348-4a6d-bc6e-a795ff80bebf)

* Only '30s' are left.

![image](https://github.com/user-attachments/assets/5c614e96-0fda-479f-becb-f9cb49544118)
![image](https://github.com/user-attachments/assets/f0c83c09-4592-4265-815f-8e0d0e80e9b2)

* We need prime numbers.

![image](https://github.com/user-attachments/assets/bc37b66c-8cd4-48dd-abae-affb7be451c3)
![image](https://github.com/user-attachments/assets/8a3ec25d-62d7-400c-b461-145c4aa0e3c4)

* Contradicting point. Remove the 2nd half.

![image](https://github.com/user-attachments/assets/20b4296d-17a3-41bf-8377-a6725ce7bc91)
![image](https://github.com/user-attachments/assets/072bb06e-3cd0-43b1-a593-d99b659fd6f9)
![image](https://github.com/user-attachments/assets/72875ee9-bb70-400e-9206-def2acbe94f3)
![image](https://github.com/user-attachments/assets/354d8300-d2b3-4c4a-9dc1-aafa96274a11)
![image](https://github.com/user-attachments/assets/f1a1f027-ec18-4364-91b2-9e0ad4d4fcfa)

* Arrange the data in **ascending order**.
* Questions -> If conditions -> We have to make cases.

![image](https://github.com/user-attachments/assets/9bb4601e-fab2-4a1d-925c-661ce134f2aa)
![image](https://github.com/user-attachments/assets/08d92f58-a5f4-41fe-a42b-f08470814afe)
![image](https://github.com/user-attachments/assets/e53f84d5-d773-424f-8896-671612daa375)

* When we work on 'P1 and P3', we will automatically get 'P2'.
* '2%, 3%' are coming in 'P3' only.
* '14%' is coming in 'P1' only.

![image](https://github.com/user-attachments/assets/d8f22a45-13e8-407e-b361-b350bb56eea0)
![image](https://github.com/user-attachments/assets/f4266f9a-ea8e-4428-91ec-ed9f8ffc0199)

* T9 -> P1 or P2 -> CBT.[1] [Answer]

![image](https://github.com/user-attachments/assets/5bb379a2-fa3c-4235-8743-e8587c957314)
![image](https://github.com/user-attachments/assets/b78f3398-1b67-42b9-8e98-c70d96986e4f)

* Case '3' only left.
* P2.[2] [Answer]
* T4, T11, T12 -> More than '2'. [3] [Answer]
* Option **4/d**. [4] [Answer]
* P3. [5] [Answer]

![image](https://github.com/user-attachments/assets/f337bf61-31ea-472d-b41b-dc12a3882828)
![image](https://github.com/user-attachments/assets/f38e1054-163c-457d-b9ca-ac15dca5a4f6)

* Answers.

![image](https://github.com/user-attachments/assets/dad3239d-725d-48ad-af91-c9047fa8b08f)
![image](https://github.com/user-attachments/assets/72eb2aa7-2928-4a09-bc6b-41bf6ac3e27b)
![image](https://github.com/user-attachments/assets/fd2420ed-3561-49a7-bdb5-9b6c5fda8862)
![image](https://github.com/user-attachments/assets/29eb6d9b-bb19-4056-9f72-cbda679a9639)

* Distribution -> Chocolate distribution.

![image](https://github.com/user-attachments/assets/10123307-c426-48d2-bd25-65645175342d)
![image](https://github.com/user-attachments/assets/e8ae587c-6335-4322-b28a-8aca96a4ab78)

* One point we have to cross check is that if one of the student count for each subject is more than '29' or not. It is not, so '29' is the answer here. 
* Atleast '1' examination -> No '0' examination case here.
* '1' examination = '1' chocolate. [Here]
* As there is no '0' examination case here, so we cannot leave anyone empty or '0'.

![image](https://github.com/user-attachments/assets/775183d3-3ecb-421f-822e-cb9d8460fe2f)
![image](https://github.com/user-attachments/assets/2456b7a9-9618-42be-8c14-b937f363d746)
![image](https://github.com/user-attachments/assets/939ca888-0764-4524-b525-b9d9853b74f0)

* Min. of '90' people will have atleast '1' chocolate each.

![image](https://github.com/user-attachments/assets/a4cd999a-b24b-4666-b073-02f7472a9c43)
![image](https://github.com/user-attachments/assets/b4062fc2-f8be-45ac-ae11-9f8d8c5fcea4)
![image](https://github.com/user-attachments/assets/08030861-9819-486d-a7cd-0796fc67c98a)
![image](https://github.com/user-attachments/assets/a52d9f2e-8f8e-4f7b-af0b-19386762756d)
![image](https://github.com/user-attachments/assets/68cb2a52-0d8e-4057-a7b1-c0951b7a5536)
![image](https://github.com/user-attachments/assets/ce5122fd-b25a-41ef-837e-0976dc7704aa)

* In 'E', no students are left with '1' chocolate. They all have '2' chocolates now. So 'E' is '0'.

![image](https://github.com/user-attachments/assets/b6ac8b0e-e383-4f62-95f3-8d67c71d3dda)

* Minimize.
* [1] [Answer]

![image](https://github.com/user-attachments/assets/c6774996-1863-4449-b85e-363dc737225e)

* We have to maximize '1' chocolate people.
* '1' people has given a max. of '5' exams.
* We want to quickly finish the '210' chocolates left.
* '1' student can have a max. of '5' chocolate.
* Whatever min. data we will have that will restrict us further.
* '50' will restrict us in 'A'. Max of '5' chocolate can be given to '50' students only. We cannot go more than '50'.
* We have to keep track of the **limitations** when we are doing **maximum/maximizing**.

![image](https://github.com/user-attachments/assets/7d0502b8-b2a2-4c7e-8f48-cc20ed805833)
![image](https://github.com/user-attachments/assets/30751baf-46fd-4048-9bc4-7279d88e50c5)
![image](https://github.com/user-attachments/assets/65b40ee1-8db6-4ee4-820b-b28fc9af9bcc)

* After '5', next best is '4'.

![image](https://github.com/user-attachments/assets/8376dbaa-cfaf-40b5-9204-b59a10628c6f)

* Limiting factor in 'B' -> 50.

![image](https://github.com/user-attachments/assets/1bea1121-06e9-4307-a586-635d827167f3)
![image](https://github.com/user-attachments/assets/09e08b3a-b72a-4cc7-994e-6fe2e46ad8b3)

* Limiting factor in 'C' -> 50.
* Maximizing.
* [2] [Answer]

![image](https://github.com/user-attachments/assets/80ad530d-eabc-417a-9eeb-fdd956e63591)

* While solving "Q2', none got '3' chocolates in 'B'. So, 'B = 0'.

![image](https://github.com/user-attachments/assets/be5aeaaa-6c52-4295-961b-bc7ffb7b5096)
![image](https://github.com/user-attachments/assets/d0424f48-e429-414e-b2ec-756887792461)

* None got '4' chocolates in 'D'. So, 'D = 0'.

![image](https://github.com/user-attachments/assets/2c5150cf-8901-4b55-8610-2dd3a2673275)

* 0 + 0 -> 0 -> option **D**. [3] [Answer]

![image](https://github.com/user-attachments/assets/3b7a66a0-2c40-4395-9fbb-54315e308290)

* We want to maximize.

![image](https://github.com/user-attachments/assets/c470ab1c-2add-47de-a066-d93b57a3a37b)
![image](https://github.com/user-attachments/assets/ade0c10a-e7ff-4cd6-a998-08c54f65e0e2)
![image](https://github.com/user-attachments/assets/e3b412be-002b-4434-b176-533dc1b1148a)

* In 'E', '100' students can easily get '5' chocolates each.

![image](https://github.com/user-attachments/assets/4023f534-29ee-41c9-bc2c-2780d855e396)
![image](https://github.com/user-attachments/assets/1aaa8ed6-d829-4dcd-a3c8-0557c74e9a3c)

* 249. [4] [Answer]

![image](https://github.com/user-attachments/assets/639792a4-772c-43bc-8bc7-5011310b5e69)
![image](https://github.com/user-attachments/assets/5b99e082-34bf-40e4-99bd-54d750f7ee5d)
![image](https://github.com/user-attachments/assets/96beb093-d90f-4c2d-b431-f1acdfafed0a)

















### Practice Questio ns

![image](https://github.com/user-attachments/assets/b741f7da-a621-4d87-b8ed-2c091246bba7)
![image](https://github.com/user-attachments/assets/7898c8ed-5812-4edb-b9ed-04dba5996d36)

* 12 -> 1 + 2 + 4 + 5.

![image](https://github.com/user-attachments/assets/63501256-dd1d-428d-a10d-370c86673231)

* 20 -> 5 * 4.
* White ball picking frequency will be '4'. 
* White ball will be picked '4' times. 

![image](https://github.com/user-attachments/assets/47b10867-edc5-4cd4-a5f3-feb139762901)
![image](https://github.com/user-attachments/assets/d96461c1-8bc0-4a54-a1b4-4065afbcecb7)

* 3 + 2 -> 5 -> Point '6'.
* 'A and B' score is the **same**.

![image](https://github.com/user-attachments/assets/23c91d51-bcab-47e4-bd32-4e773f83f0fd)
![image](https://github.com/user-attachments/assets/36fd7246-fe66-49c5-9c4e-f4e676d69c25)

* '2' can come in rows '1, 3 and 4' only once(1).
* '5' can come in rows '1, 3 and 4' only once(1).

![image](https://github.com/user-attachments/assets/2eed4eb6-883b-4cfe-b1fc-0e2aa756bb5f)
![image](https://github.com/user-attachments/assets/058a653e-157e-4437-98ab-faf6d0bc56e3)
![image](https://github.com/user-attachments/assets/e3673471-b0e3-4bfe-8e0a-312dbfa24923)
![image](https://github.com/user-attachments/assets/cf0bd103-b50f-4c19-a28b-fdf53f03f424)

* Set-1

![image](https://github.com/user-attachments/assets/eb67f834-d169-4b22-af4b-f599d7c7284d)
![image](https://github.com/user-attachments/assets/ef33ded7-bb81-4be8-a532-16f9f8cb7de5)
![image](https://github.com/user-attachments/assets/e5f04a7c-9193-4b18-9ba6-ff1bf4353397)
![image](https://github.com/user-attachments/assets/a0cd2ba7-ab91-4fdb-a20b-eb351e7eb26c)
![image](https://github.com/user-attachments/assets/f9954971-b1cd-4718-943b-35a890aaf097)
![image](https://github.com/user-attachments/assets/17d9d4ca-580b-4697-bb36-2c8382b64284)

* You Divided -> Pavan.
* 70 * 4 -> 280.
* No. of matches played must be lower than '20'.
* '4' matches won by 'Me united' which akhil is supporting. So in every case we have to add '4' to it.
* 4 + 4 + 12 -> 20 -> Not valid -> Should be less than 20.

![image](https://github.com/user-attachments/assets/f7c5f1b4-56a2-446b-b1d3-6e89805a9ef7)
![image](https://github.com/user-attachments/assets/85af1aba-e8a0-4914-848d-5be2ec3e6324)

* 4 + 6 + 7 -> 17. 
* 4 + 8 + 2 -> 14.
* This is for 'Jan' month.

![image](https://github.com/user-attachments/assets/7b8cdef0-9529-4190-b083-6cd3b3792069)

* 70 * 3 -> 210.
* This is for 'Feb' month.

![image](https://github.com/user-attachments/assets/4ddeae95-cf6e-41c4-b8fa-25341816c254)
![image](https://github.com/user-attachments/assets/75e3c128-10ee-453d-a9b7-4c5cb3949acd)

* 70 * 9 -> 630.
* This is for 'Mar' month.

![image](https://github.com/user-attachments/assets/e11c45ae-ca39-45f6-8e0f-7d24b3766a8f)

* All of the no. of matches(M) is **distinct**.
* All of the no. of wins(W) is also **distinct**.
* So '11' is not possible in 'Feb' month. Remove that case.
* So '1' is not possible in 'Feb' month. Remove that case.

![image](https://github.com/user-attachments/assets/f6a20c63-697b-4003-acfd-5aaa7cc9bdb7)

* So '14' is not possible in 'Jan' month. Remove that case.

![image](https://github.com/user-attachments/assets/94698d4d-1d4f-4ef8-8870-f5b98c6c281f)
![image](https://github.com/user-attachments/assets/4041a127-1959-4c82-bae2-9d81077fe870)
![image](https://github.com/user-attachments/assets/ad9948a6-a08b-4c56-9742-5cc3153a48f9)

* '6' wins already happened in 'Jan' month, so  remove it from 'apr' case.
* 1 + 4 + 16 -> 21 -> Greater than '20' -> Not possible.

![image](https://github.com/user-attachments/assets/b664a40b-81ec-413d-8789-cf081d7f1ae9)
![image](https://github.com/user-attachments/assets/433fdca9-79b3-4fe1-a500-7a5d9522b3ab)

* 1 + 11 + 10 -> 22 -> Greater than '20' -> Not possible.
* This is for 'May' month.

![image](https://github.com/user-attachments/assets/8bf4dcd4-af24-4e0d-b316-15452f499537)
![image](https://github.com/user-attachments/assets/e2ff01ed-239a-4776-ad2d-8084a66d0754)

* 6 + 11 + 2 -> 19 -> Not Greater than '20' -> Possible.
* '6' wins already happened in 'Jan' month, so  remove it from 'june' case.
* This is for 'June' month.

![image](https://github.com/user-attachments/assets/80eb1107-738e-4219-b120-77d9659915bc)

* '3' wins already happened in 'Feb' month, so  remove it from 'May' case.
* '16' matches already happened in 'may' month, so  remove it from 'june' case.

![image](https://github.com/user-attachments/assets/172c59a1-6db8-4740-a7cd-ed5d5b065163)

* '10' wins already happened in 'june' month, so  remove it from 'april' case.

![image](https://github.com/user-attachments/assets/1ceb6b85-f727-438a-9916-c5512524027f)
![image](https://github.com/user-attachments/assets/757261b5-30b7-463d-bdbf-3bbd62045a50)
![image](https://github.com/user-attachments/assets/dadde2de-31fe-4cde-8d60-85d385b3a3c7)

* Total draws -> 7 + 8 + 1 + 6 + 1 + 1 -> 24. [1] [Answer]

![image](https://github.com/user-attachments/assets/80466e3c-d105-4eb8-bfee-d489ad297fe9)

* We want to maximize.
* June -> 10/23. [2] [Answer]
* You divided won games -> 33.
* Me united won games -> 4 + 3 + 9 + 1 + 10 + 2 -> 29.
* Diff -> 33 - 29 -> 4.  [3] [Answer]

![image](https://github.com/user-attachments/assets/fb2ec90b-5ed0-42ca-9858-c43276099b38)
![image](https://github.com/user-attachments/assets/6b384510-5eb0-4284-9aac-9b0b13f06ab6)

* Jan -> 31days -> 17 * 2 = 34days -> Not possible.
* Feb -> 28days -> 14 * 2 = 28days -> Possible.
* Mar -> 31days -> 11 * 2 = 22days -> Not Possible.
* Apr -> 30days -> 15 * 2 = 30days -> Possible.
* May -> 31days -> 16 * 2 = 32days -> Possibility -> Possible.
* June -> 30days -> 23 * 2 = 46days -> Not Possible.
* Feb, Apr, May -> 3. [4] [Answer]

![image](https://github.com/user-attachments/assets/db70294a-bf73-4640-a7c0-0def491bbe56)

* Jan -> 17 matches. [5] [Answer]
* Set-2.

![image](https://github.com/user-attachments/assets/d55634b0-a837-48dc-9d00-3ada95e25499)
![image](https://github.com/user-attachments/assets/d77fcdea-8457-4912-ac7f-c11fabc4b537)
![image](https://github.com/user-attachments/assets/c2e5b65f-e043-43c8-80f2-99ae5cfe360e)

* When the tax amt. is doubled then the tax rate is also doubled.

![image](https://github.com/user-attachments/assets/d2c47706-a7ff-4cd6-bb48-49f00b94ba8d)
![image](https://github.com/user-attachments/assets/b838e89c-138a-427b-a392-8662b57e3e87)

*  Tax rate -> x %.
*  Tax rate -> 2x %.

![image](https://github.com/user-attachments/assets/90d30364-2bf3-4ed9-bc70-ed1c0de5ce20)
![image](https://github.com/user-attachments/assets/eaa9cd82-8b97-4963-b617-c9508ed37313)

* 'A' is paying taxes which means that 'A' is earning more than '12000'.

![image](https://github.com/user-attachments/assets/aa5cc975-b484-4de0-9813-ca9a8dc69a0c)
![image](https://github.com/user-attachments/assets/b4722855-eb35-426e-84de-1c63833105a6)
![image](https://github.com/user-attachments/assets/b6c328ee-11b4-4be0-8323-3f7c882b4f01)

* A -> 3b -> 300.
* A -> 13b -> 1300.
* A -> 45b -> 4500.
* A -> 139b -> 13900.

![image](https://github.com/user-attachments/assets/192f7ef6-099e-4628-823b-a86a973c3d5e)
![image](https://github.com/user-attachments/assets/b7f9cf80-a74a-4bd3-87d4-42a838a0ec73)

* P = 25000. [1] [Answer] 

![image](https://github.com/user-attachments/assets/79714854-bd26-48fc-a46d-6df9a0ed121e)
![image](https://github.com/user-attachments/assets/5327859c-7de6-4a7c-8c78-e2274cd56a73)

* Q = 50000. [2] [Answer] 

![image](https://github.com/user-attachments/assets/595b0ddb-3b49-4120-b521-9a2d936fbc83)
![image](https://github.com/user-attachments/assets/ca4dbd9d-60b8-43ed-b733-0e1da87c83cf)
![image](https://github.com/user-attachments/assets/3163adfb-b421-49fb-a46b-b9863fe4b07c)

* Income of '69000' -> Tax is '13900'.
* The remaining '31000' will be taxed at '40%' for sure.
* Income of '31000' -> Taxed at 49% -> Tax is '12400'.
* 26300. [5] [Answer] 
* Set-3.

![image](https://github.com/user-attachments/assets/3d5e6b3c-d338-44d8-8b71-dc4933a054fa)
![image](https://github.com/user-attachments/assets/9582b316-477b-4986-ad87-225ce4e5909e)
![image](https://github.com/user-attachments/assets/d7e9daa5-691d-46e7-b0cd-2b222a820ee9)
![image](https://github.com/user-attachments/assets/6cc81507-29e0-4fff-90ab-d441748b0475)

* Diff. between the no. of books between any '2' people is multiple of '2, 4, ..'
* Z+ -> It is an integer.

![image](https://github.com/user-attachments/assets/ab8d5ce1-e40d-4b0d-bf51-fa0a7d4a3fff)
![image](https://github.com/user-attachments/assets/242d7d67-61fa-4eb4-aeb0-d67cc32f661b)

* LCM -> 2k, 3k, 4k, 5k -> 60k
* The diff. between the '2' books should be a multiple of '60'.

![image](https://github.com/user-attachments/assets/f243ff94-8991-405c-b3be-917bf533dfb7)

* 180 -> 60k -> 60 * 3 = 180.

![image](https://github.com/user-attachments/assets/675e28e9-df87-4292-b425-773d1218c559)
![image](https://github.com/user-attachments/assets/7bf9635e-cc66-4712-a133-828e903cdc13)
![image](https://github.com/user-attachments/assets/96ebb724-d372-4de7-9e6f-61a07cbfd0f0)

* Case '2' is only possible. Case '1 and 3' are not possible.

![image](https://github.com/user-attachments/assets/1bf0af5c-e1c0-4364-be76-c46696d3939b)
![image](https://github.com/user-attachments/assets/7930ff0c-e7d4-4f8f-b148-9a600d674726)

* B - C = 180.
* B > C.
* D = A + E.

![image](https://github.com/user-attachments/assets/8cf0453a-9ae2-481a-af39-53c66d49e329)
![image](https://github.com/user-attachments/assets/7fbcaa77-018c-4c06-b995-63a362300a48)

* Set-4.

![image](https://github.com/user-attachments/assets/77b30cfb-4704-48c4-ac78-dae857e8e628)
![image](https://github.com/user-attachments/assets/a2138f11-5978-47c7-91a0-0ea3f20aaa46)
![image](https://github.com/user-attachments/assets/c8ea3078-1426-4b50-953b-d33b5c6a2d7f)

* Only group 'B' -> 0.
* There is nothing as only 'B'.
* Only group 'D' -> 0.
* There is nothing as only 'D'.

![image](https://github.com/user-attachments/assets/447295a7-b89f-4953-bd5e-9134634d96fd)
![image](https://github.com/user-attachments/assets/9f8ddb35-5e53-42cb-a7d5-36cefc48214c)

* Both 'B and D' -> f -> 15.
* A and C -> c + d + e + f.
* A and C but not D -> c + d.
* Only C and D -> h.
* B and C -> d + f.

![image](https://github.com/user-attachments/assets/6e6ce892-3a61-4554-a36c-47ec59db52c3)
![image](https://github.com/user-attachments/assets/bde10fa7-4998-4ffb-af53-df33d20c155a)

* Both 'A and B' -> b + d + f -> 40.
* 'C' but not 'A' -> g +  h -> 55.

![image](https://github.com/user-attachments/assets/d0ad2d21-77e0-4b91-9b0e-3b8dde00ccd1)
![image](https://github.com/user-attachments/assets/4f230508-1ff5-4a1c-a617-5099dc538b6a)
![image](https://github.com/user-attachments/assets/ce3b3354-a39d-4b93-9769-e11a95ebc549)
![image](https://github.com/user-attachments/assets/2e0258ce-b80b-445d-9d57-560712ceaf30)
![image](https://github.com/user-attachments/assets/79909034-da5a-463f-935e-7d33598c172b)
![image](https://github.com/user-attachments/assets/70c75cb7-b7da-4054-9da5-0e26325679f6)

* 35. [1] [Answer]
* Definitely decrease -> 55 + 5 + 20 -> 80. [2] [Answer]

![image](https://github.com/user-attachments/assets/62b7b01d-cd2b-4820-847d-3367f0ee8f47)

* Definitely increase -> 15 + 25 + 30 -> 70. [3] [Answer]

![image](https://github.com/user-attachments/assets/fda191d1-33c6-440c-a195-c06b33ea1007)
![image](https://github.com/user-attachments/assets/a364078d-0738-45b1-bdc0-67fee4f44675)
![image](https://github.com/user-attachments/assets/8dca5631-894a-4309-9e23-503c36550f3d)
![image](https://github.com/user-attachments/assets/686302aa-8f7c-4e8c-a9a5-dc7be6ada7b7)

* Set-5.

![image](https://github.com/user-attachments/assets/d48cd460-0338-48f7-a836-7e0552e64f8e)
![image](https://github.com/user-attachments/assets/dc5dbbdb-8233-48db-989a-49cf688f6f76)

* Only  -> Hinting to venn diagram.

![image](https://github.com/user-attachments/assets/181b69e9-f533-4b3a-8373-40bcb1cf7292)

* N -> 140 * 2 + 60 -> 340.
* S -> 120 + 100 + 80 -> 300.
* C -> 220 + 120 + 60 -> 400.
* I -> 100 + 220 + 180 -> 500.

![image](https://github.com/user-attachments/assets/28c37dbb-73dc-41e7-8688-eb6e83e58483)

* We want to maximize it.
* Max. can be '300' only because of south indian(S) food. Any no. more than '240' will make it more than '300'.
* 240 + 60 -> 300.

![image](https://github.com/user-attachments/assets/7ba7b0bc-4694-40e8-926d-036bfa43f16b)

* 240 + 60 + 40 -> 340.

![image](https://github.com/user-attachments/assets/9bf24fcf-da0c-40a8-a384-1a570b233a17)

* 240 + 60 + 20 + 200 -> 520 > 500 -> Not possible.

![image](https://github.com/user-attachments/assets/142d0fe4-8bbe-46dd-a1aa-b0458a044e96)
![image](https://github.com/user-attachments/assets/22d05248-8fd0-4129-a3e7-a3a61e1dbac6)

* S -> 80 - 60 -> 20.
* N -> 60 - 40 -> 20.
* N and S -> 20.

![image](https://github.com/user-attachments/assets/7a8f7c8e-2bc2-4682-a296-ed06d10de36f)

* 280. [2] [Answer]

![image](https://github.com/user-attachments/assets/7e14c5d7-1eb5-41ff-982f-5ea0de4cfd15)
![image](https://github.com/user-attachments/assets/df27ca21-4bcb-41f8-877a-0fbaa06ebb9d)

* We will get '520' in 'I'. We have to make some changes.

![image](https://github.com/user-attachments/assets/c481823f-07c7-4536-a2a4-3032ab681731)

* Eating all '3' foods -. 0.

![image](https://github.com/user-attachments/assets/484d143d-ca3c-4e1c-b8b2-93c8c6c76d77)

* Set-6. [Dout]

![image](https://github.com/user-attachments/assets/ae1351ed-0af3-42a0-bc3e-9a9af875107b)
![image](https://github.com/user-attachments/assets/04415ccf-a493-4e65-8b38-1c82201ac35a)

* No. of matches -> 15.

![image](https://github.com/user-attachments/assets/20c9c7b2-fddc-4ed0-9205-8b28f6ce736b)
![image](https://github.com/user-attachments/assets/76d95efe-d968-495c-bb3e-c7fcb6d1727c)
![image](https://github.com/user-attachments/assets/4ef79873-9196-4744-b6af-37d92d9245de)

* Points are **distinct**.
* Total draws -> 4.

![image](https://github.com/user-attachments/assets/b5d3591b-6757-4008-8605-62c00499898a)
![image](https://github.com/user-attachments/assets/7be04d52-cb71-4b62-a4c6-951c8172e858)
![image](https://github.com/user-attachments/assets/22406e78-e060-4dac-b734-081018dd9856)
![image](https://github.com/user-attachments/assets/0bbf6a76-0355-4236-a464-5aaf77188746)
![image](https://github.com/user-attachments/assets/8f2e232b-f65e-4231-b2c6-622d0b4c7400)
![image](https://github.com/user-attachments/assets/42da1062-87f5-4025-b549-cd661f645cfa)

* Draw -> Each participant gets '1' point each.
* Total points -> 41.

![image](https://github.com/user-attachments/assets/027df49f-a84c-407a-8afb-ffb864e28a62)
![image](https://github.com/user-attachments/assets/28317260-5cbc-45f8-87e5-2814fcc21bb9)
![image](https://github.com/user-attachments/assets/0c8d47c8-5571-4e77-8501-8c187a876bca)

* 'F' only played '1' draw. So '13-2' is not possible.

![image](https://github.com/user-attachments/assets/82234182-e2c7-45b6-9d37-7edd47625d27)
![image](https://github.com/user-attachments/assets/5b09f6b7-505b-4f5a-8cec-968542753eb0)
![image](https://github.com/user-attachments/assets/f0698115-39e1-4a1c-9a40-df7159f2dc0c)
![image](https://github.com/user-attachments/assets/24ccc60c-87a0-4812-a844-0d7eedc87b40)
![image](https://github.com/user-attachments/assets/fac02fc3-34ad-4293-9d1b-b7827301590e)
![image](https://github.com/user-attachments/assets/d85700e5-e2d1-4b8c-b4b7-027dfc73e532)

* Goals against 'F' -> 2 + 2 + 1 + 2 -> 7.
* Total Goal against -> 37.
* Total Goal scored -> 37.
* Goals for 'F' -> 2 + 1 -> 3.
* Goals for 'C' -> 37 - 28 -> 9.

![image](https://github.com/user-attachments/assets/f2e22450-0b00-45de-9df0-6a56d3d97130)

* 'A-E' cannot have a draw because 'E' had no draws.
* Goals for 'A' -> 3 + 2 + 2 -> 7.

![image](https://github.com/user-attachments/assets/17482f22-00c2-412a-8476-c8db6405b9e3)

* Goals against 'A' -> 3 + 2 + 1 + 2 -> 8.

![image](https://github.com/user-attachments/assets/2b8f9bef-d277-4e58-a1f3-a0d017397578)
![image](https://github.com/user-attachments/assets/842ef46c-c949-4abc-ae9c-b2083cee435e)

* Goals by 'E' -> 2 + 2 -> 4. 
* Goals by 'D' -> 1 * 3 -> 3. 

![image](https://github.com/user-attachments/assets/0f842ffe-7a09-4bf0-a875-3b3e3adf5443)
![image](https://github.com/user-attachments/assets/5577d160-6b80-44b5-a42e-39ba9dc92330)
![image](https://github.com/user-attachments/assets/9049830e-9e88-4b00-b2dc-04fdc477a042)
![image](https://github.com/user-attachments/assets/9a5df4fa-9d57-4871-bc46-f37baa446953)
![image](https://github.com/user-attachments/assets/3d52c545-18be-448e-b09b-049ec83ca8b0)
![image](https://github.com/user-attachments/assets/40bb60a7-297b-4664-8691-f6cafa6622cb)

* Set-7.

![image](https://github.com/user-attachments/assets/4669c759-a3a0-495a-ac2b-45de189b1517)
![image](https://github.com/user-attachments/assets/43d1f8b2-716f-4dc9-9832-2a4309815535)
![image](https://github.com/user-attachments/assets/91b62db9-2f09-4f5e-bc43-4fd1770b38ca)
![image](https://github.com/user-attachments/assets/7f7c6960-d0b1-4cb1-a5e8-3969bbd16dd5)
![image](https://github.com/user-attachments/assets/09d71d1f-f543-41a0-9e3a-db8332b3f3c1)
![image](https://github.com/user-attachments/assets/85bc095f-5fe2-4ea8-93e4-47b85203fbf0)
![image](https://github.com/user-attachments/assets/c362ef4e-896d-4237-87b1-1ff1fbdf72fa)
![image](https://github.com/user-attachments/assets/7f69a15f-4d8a-4293-a51e-bf92adbfc110)

* 50 + 30 -> 80.

![image](https://github.com/user-attachments/assets/8cbad6ce-2485-47f9-a8a2-eda9acc31c16)
![image](https://github.com/user-attachments/assets/5411dc20-87c7-4925-ad46-0280bdd0ae05)
![image](https://github.com/user-attachments/assets/8f883377-363c-4d5a-91d0-1ca15b8c5c78)

* S1 + S2 + S3 -> 180 degree.
* S1 + S2 + S3 = S4 + S5 + S6. 

![image](https://github.com/user-attachments/assets/c5663cb3-50c1-4256-929e-204cbf3c22ff)
![image](https://github.com/user-attachments/assets/48d18520-3b3a-4db7-b11a-97c58f071117)
![image](https://github.com/user-attachments/assets/8a77df65-f051-49e9-bb08-62a03f7a3e4f)
![image](https://github.com/user-attachments/assets/065f2f80-bd8d-424b-abc8-a06bf35067b5)
![image](https://github.com/user-attachments/assets/87d2030b-4388-4ab9-bcc7-f4935daf9edc)
![image](https://github.com/user-attachments/assets/f64d3d56-8bca-4348-baa0-4f75ef2c9f3f)

* Set-8.

### Practice Test

![image](https://github.com/user-attachments/assets/5771a9f4-bfe0-4855-926a-f37ea0af7e64)
![image](https://github.com/user-attachments/assets/5a09d599-2e88-47b2-b2d3-0842c779b5ab)

* Avg < 70.
* It would be less than '280'. 

![image](https://github.com/user-attachments/assets/08d258f7-1ded-4961-89ea-953db6c29d11)

* Example to explain the last statement of the question.
* For every test, the total is less than '280'. 

![image](https://github.com/user-attachments/assets/643bd0db-400a-4363-ae6d-bc90f1528ddc)
![image](https://github.com/user-attachments/assets/7eda0f4d-0d7c-4d14-bbaa-4f3345e15dbb)

* We want to find each one(1) of the crosses in each column.

![image](https://github.com/user-attachments/assets/2d67df86-642a-4220-9999-ad0c94ba4e04)
![image](https://github.com/user-attachments/assets/576bd92b-ce5e-4f03-a639-ee8a103433a4)

* T1 -> 50 + 64 + 85 + 82 + 77 -> 358.

![image](https://github.com/user-attachments/assets/5a83ae56-979c-4661-8c95-d5ef6749cef9)

* T2 -> 63 + 51 + 85 + 68 + 88 -> 355.
* We cannot remove 'K' which is '85'. We have to remove '88'.

![image](https://github.com/user-attachments/assets/7d86e702-fe64-43cb-9b05-2828e6cbf7d7)
![image](https://github.com/user-attachments/assets/3e5ad65a-2c00-4f64-b8b2-4bec32e1f716)

* T3 -> 63 + 57 + 77 + 68 + 88 -> 353.
* We cannot remove 'K and S' which are '77 and 88'. We cannot remove anything. So this case is not possible/wrong.

![image](https://github.com/user-attachments/assets/9d78a5b5-7c21-493e-9374-2ebefda630e3)
![image](https://github.com/user-attachments/assets/56ff967f-91f4-4e9d-95ef-d4a868616e12)
![image](https://github.com/user-attachments/assets/a6c54b71-9c7c-4376-b5a2-c87cb0124d53)
![image](https://github.com/user-attachments/assets/187ae2c4-a10d-415f-9415-99cadf277e09)

* Case **II**.
* T1 -> 50 + 64 + 85 + 77 -> 276 -> Less than '280'.

![image](https://github.com/user-attachments/assets/e2a43b7d-4e59-4116-9af6-430bf63a4843)
![image](https://github.com/user-attachments/assets/9defe080-3778-41e8-9191-12802bf5febc)

* T2 -> 63 + 51 + 77 + 82 + 88 -> 361 -> 361 - 280 = 81.
* We cannot remove 'R' which is '82'. We have to remove '88' which is 'S'.

![image](https://github.com/user-attachments/assets/0bda4db1-eafb-4a1e-a9b3-53a720b2b54f)
![image](https://github.com/user-attachments/assets/6cb8bed0-6f2f-4b46-834c-07e6fbefe30a)
![image](https://github.com/user-attachments/assets/9814091b-43b4-4dcb-9b62-f9270f211c7c)

* T3 -> 63 + 57 + 68 + 68 + 88 -> 344 -> 344 - 280 = 64.
* We cannot remove 'R and S' which is '68 and 88'. We have to remove '68' which is 'K'.

![image](https://github.com/user-attachments/assets/41525520-e4ae-44c4-8dc3-a667b38cfa9c)
![image](https://github.com/user-attachments/assets/ee483886-dad0-4c5a-9d6b-038884310806)

* T4 -> 80 + 71 + 68 + 68 + 65 -> 352 -> 352 - 280 = 72.
* We cannot remove 'R, S and K' which is '68, 68 and 65'. We have to remove '80' which is 'A'.

![image](https://github.com/user-attachments/assets/a1f0252c-a6fd-4fcb-ba11-8c834d7c59d5)
![image](https://github.com/user-attachments/assets/eb8af434-888c-439e-bcb1-e9cf9b105ee5)

* Min. total score -> T4 -> 272. [1] [Answer]
* Priy  a. [2] [3] [Answer]
* Kumud. [4] [5] [Answer]

![image](https://github.com/user-attachments/assets/b2e8005b-760d-477e-9b3e-5fede8c1f472)
![image](https://github.com/user-attachments/assets/c33ae747-4fa0-411c-a62a-bf478692a85c)
![image](https://github.com/user-attachments/assets/5728b9d7-a371-418a-9a48-b00d42ec4e3c)
![image](https://github.com/user-attachments/assets/41c35f3e-e902-4217-a008-8872cc05bb19)
![image](https://github.com/user-attachments/assets/ae0ac31e-d102-4974-a60e-164ea46cdbf5)

* Total ranks -> (1 + 2 + 3 + 4 + 5 + 6 + 7 + 8) * 2 -> 72.

![image](https://github.com/user-attachments/assets/e9852d17-bf4f-4efe-a989-8f60c56c6185)
![image](https://github.com/user-attachments/assets/52792fee-56f0-45d1-a816-f2951b084769)

* M1-F1 is not possible.

![image](https://github.com/user-attachments/assets/a73cb39f-69e8-4b9b-b2fb-a6e1e0406926)
![image](https://github.com/user-attachments/assets/18b858f8-4868-415e-8df8-829f28995f1d)
![image](https://github.com/user-attachments/assets/6ebb417b-c03b-48ad-90ba-198a91760107)

* Monica -> F5 -> M2 -> Roger. [1]

![image](https://github.com/user-attachments/assets/77cb2ccc-aaa0-45ec-bd4a-92c80d549a50)
![image](https://github.com/user-attachments/assets/29bc1edd-c493-4699-9387-0924e5334755)
![image](https://github.com/user-attachments/assets/e6676b71-affb-4411-8e7c-7d70f2590cf3)

* 6 ^ 3 -> 216.

![image](https://github.com/user-attachments/assets/adda0b0d-68a7-41ce-88ef-9eae987b0a71)
![image](https://github.com/user-attachments/assets/3003f158-6610-477d-b09a-405fc6611c9f)
![image](https://github.com/user-attachments/assets/a6f3d8f3-fcdd-41a0-86c4-1c06974ad3ee)

* Gap between 1st and 2nd layer columns -> 36 -> Multiples of '36'.

![image](https://github.com/user-attachments/assets/829b3716-1559-4f28-a14e-31082b55d89e)
![image](https://github.com/user-attachments/assets/f489be1b-f9cc-49ab-8932-a2c3ad90e86e)

* 108 + 36 -> 144

![image](https://github.com/user-attachments/assets/908b720c-de75-41b0-9ce9-d7e8809e46ab)

* 72 + 36 -> 108.
* When we are going to the **core**, we are trying to go from each and every side.

![image](https://github.com/user-attachments/assets/6ea0ad0b-24e3-4d6b-a81c-e7fd27c0a6cf)

* From everyside, '2' layers are gone.

![image](https://github.com/user-attachments/assets/f04131e0-2537-48ed-bbf2-d23721deb0d0)
![image](https://github.com/user-attachments/assets/4a555030-4093-473c-9b08-9ac1cdf76d33)

* We will reduce using multiples of '36'.

![image](https://github.com/user-attachments/assets/cb51c100-a657-4fff-a5dc-e69f00d0c5d1)

* 107 - 36 -> 71 -> They are touching each other.
* Option **D** -> They are not touching each other.

![image](https://github.com/user-attachments/assets/f8d75cae-5448-49d5-8657-3bbf7bbafa9e)

* 37, 72 -> Both are in 3rd layer.
* Shortest distance has to be on the same plane. Closest possible points should be there.

![image](https://github.com/user-attachments/assets/cb09befc-2588-40ac-a79c-67156bbd5889)
![image](https://github.com/user-attachments/assets/280ee72e-70d1-4f29-b5c5-f64eb6f8d851)

* 36, 72 -> Highest numbers.

![image](https://github.com/user-attachments/assets/d2ae4b81-383f-4a44-8687-886967fee84a)
![image](https://github.com/user-attachments/assets/4a83251b-947b-4e6a-afbc-3e2ca0bad302)

* We want to minimize the sum of '5, 6, 7, 8'. To do that, we need to maximize '3 and 4'. To do that, we need to manimize '1 and 2'.
* Min. is '10'.
* Max. is '50'.

![image](https://github.com/user-attachments/assets/2d356010-a48f-4b9c-9202-01dead60e4af)
![image](https://github.com/user-attachments/assets/8a932aa3-a7ea-4b12-8280-810692015527)
![image](https://github.com/user-attachments/assets/aa206454-8fe5-4b0a-9436-8362783420ed)

* '7 and 8' dont have any min. values. 

![image](https://github.com/user-attachments/assets/2a1140f1-d60b-445b-a504-cc94a104a2a5)
![image](https://github.com/user-attachments/assets/0c1a841c-4d1b-4e76-a80a-0af76c2f2fdd)

* Total score in the '8' matches -> 170 + 154 -> 324

![image](https://github.com/user-attachments/assets/735e45e5-d155-471b-9a12-b0e50255cdec)

* 3 -> 50. [Let]
* 6 -> 50. [Let]
* '4 + 5' -> 191 - (50 * 2) -> 91.
* R4 - R5 -> 8 -> Even -> Either both are **even(e)** or both are **odd(o)**.
* 91 -> Not possible -> Cannot come from 'e + e' Or 'o + o'.

![image](https://github.com/user-attachments/assets/518997fe-8e6b-44df-98ab-cd5161687306)
![image](https://github.com/user-attachments/assets/59253c53-e646-43b4-b6ac-908040152ce9)
![image](https://github.com/user-attachments/assets/c1da2145-746c-4b20-ab4c-b5a7709ffdb5)

* 94 - 51 -> 43.
* x = 51, y= 43 -> 'x' is not possible as '51 > 50' -> The limit/max is '50' only. 

![image](https://github.com/user-attachments/assets/1fe79232-aac4-466f-a3e6-6c77cb441b9e)
![image](https://github.com/user-attachments/assets/c72d2467-0f82-4127-9adb-0984e3129d73)

* Option **B**.

![image](https://github.com/user-attachments/assets/85d1e709-636b-4ab0-a151-c6e4bc5273ae)
![image](https://github.com/user-attachments/assets/bb2c11fa-8ccc-417d-8fab-c1b03dd55607)

* We got sum as '270'.
* W want sum as '235'.
* 270 - 35 -> 235.

![image](https://github.com/user-attachments/assets/04a077e1-3a6c-4250-b245-4a3d92780250)
![image](https://github.com/user-attachments/assets/fec23767-1c0a-4a0b-a1d2-8c76789295f0)
![image](https://github.com/user-attachments/assets/108f3ebd-2aeb-4c60-80c8-55007b33eb9c)
![image](https://github.com/user-attachments/assets/ef7c835d-536a-45b4-abab-5fb7f982800a)

* Option **B**.

![image](https://github.com/user-attachments/assets/33608469-1ea2-4a08-89ef-0c357eb7e148)
![image](https://github.com/user-attachments/assets/dd2e012f-9f4f-4020-8223-0b22d8915b5b)
![image](https://github.com/user-attachments/assets/b3922745-612f-4602-bb24-b15539dc7cff)
![image](https://github.com/user-attachments/assets/29e8e97a-ff21-45f8-aff4-0d09014edb5c)

* We have to maximize '1,2,7,8', so that '3,4,5,6' are minimized.
* We cannot take all of them as '50' because **distinct** nos have been asked.
* Option **D**.

![image](https://github.com/user-attachments/assets/33a268e1-ddc1-495f-b5e4-113ef0358fe0)
![image](https://github.com/user-attachments/assets/93093230-9f7f-4d6f-ad40-12e06404a53b)

* T -> 165 + 181 -> 346
* For maximizing 'T6' -> 3,4,5,6 -> '50' each.

![image](https://github.com/user-attachments/assets/9cf3b346-d8f9-4fe3-aa8d-77441dabbade)
![image](https://github.com/user-attachments/assets/d2be82fb-a325-44c1-a9c8-318dc739c012)

* For minimizing 'T6' -> 1,2,7,8 -> '50' each.
* 146<= values <= 200.
* Option **C** -> 4.

![image](https://github.com/user-attachments/assets/121de80f-d375-4b64-a6f5-3f4247291641)
![image](https://github.com/user-attachments/assets/7ef4d3bc-675e-481b-be8f-15b674dc2451)
![image](https://github.com/user-attachments/assets/7c7f2add-3762-4052-9430-199e81ae0c0d)
![image](https://github.com/user-attachments/assets/f118cd45-bbe9-48a9-b486-079dfe0d40ec)
![image](https://github.com/user-attachments/assets/93ea241f-8b2e-44e6-a5b3-a02aae8ce17a)
![image](https://github.com/user-attachments/assets/0b1ca5e7-a346-4166-b146-5bd471ff80dd)
![image](https://github.com/user-attachments/assets/73ddc8cc-599e-4a6c-a838-138fb3b7950d)
![image](https://github.com/user-attachments/assets/18a42d9d-f1a1-4e58-83e6-3d1ecca3bafe)

* Answers.

![image](https://github.com/user-attachments/assets/fea4ed5a-2984-4173-8532-7109ddc24dbb)
![image](https://github.com/user-attachments/assets/9c4f6ad5-0eb9-441a-aeb0-1970976d131e)
![image](https://github.com/user-attachments/assets/4fca64cc-7199-45b6-b0a0-d1facc3d94c9)

* 'a' min. is not possible.

![image](https://github.com/user-attachments/assets/829621b2-d7c3-4246-9552-5c5e7ac121e7)
![image](https://github.com/user-attachments/assets/d5fcb50b-ba4c-4711-b38b-055a2bc40c05)

* [Concept] [Logic]

![image](https://github.com/user-attachments/assets/3e4d2d7c-12d1-47f0-b9bf-de4665bf841c)
![image](https://github.com/user-attachments/assets/5b031622-4490-4bf8-a74f-6c7ee366fe45)

* To compensate '1' ticket of 'A1' category we need to buy '10' tickets of 'A4' category.

![image](https://github.com/user-attachments/assets/92eac90f-5424-4283-8259-89f56951b584)

* With purchasing 'A1' category ticket, we are not minimizing 'A4' category tickets, we are maximizing 'A4' category tickets.
* We are not minimizing here.

![image](https://github.com/user-attachments/assets/030d9d8b-fe41-4124-a035-685c344bbfd7)

* We are not minimizing here.

![image](https://github.com/user-attachments/assets/ea4d745e-8f62-4d83-a0ce-918c112bf935)

* We are now minimizing here.

![image](https://github.com/user-attachments/assets/b5efdf33-2db1-420d-9f19-9abbc6226e79)

* We don't need to buy 'A1 and A2' tickets.

![image](https://github.com/user-attachments/assets/99e9b4f8-8f4e-4462-936d-fb33e15b183e)
![image](https://github.com/user-attachments/assets/590dbe1a-bdf6-40ba-a5e4-bb8e1f7902f1)

* Now we can minimize.

![image](https://github.com/user-attachments/assets/560d7eec-6d57-438c-a1a8-4048ac966186)

* 'C and D' are '0'.

![image](https://github.com/user-attachments/assets/7f22d3ec-5859-41f4-bb8c-d59782efd40e)
![image](https://github.com/user-attachments/assets/beafd31c-8e1e-4dad-a972-4adb208e1dd9)

* 'a' min. is '55'.

![image](https://github.com/user-attachments/assets/fea58b79-6b83-40e8-b8af-7f9332456423)
![image](https://github.com/user-attachments/assets/0887ec7e-8e3e-4a78-ac89-bf8d923e8c91)

* In very less people we want to achieve that '90000' deficit.

![image](https://github.com/user-attachments/assets/a7b45945-f6bb-4667-8fe1-b74621ec0596)

* 2250 - 750 -> 1500.
* We are reducing every ticket by '1500'.

![image](https://github.com/user-attachments/assets/9b737a94-600f-4359-b8a9-2c522267537c)

* Method **1**.

![image](https://github.com/user-attachments/assets/eb5b3c89-b242-4186-bb7f-f7185c591af0)

* Method **2**.

![image](https://github.com/user-attachments/assets/ad2806ee-6bd5-4710-90fa-624c07b7793a)
![image](https://github.com/user-attachments/assets/0a9be29d-6f78-42c0-8442-c350c711dba9)

* To minimize 'd', we will maximize 'k'.

![image](https://github.com/user-attachments/assets/8f5f3fc2-4e86-4ee0-b76e-28ff815d7bb0)

* 40/5 -> 8. [Answer]

![image](https://github.com/user-attachments/assets/302790aa-f949-48ce-9481-3c966a6f0ce4)

* 83' is not a multiple of '3'.
* 3d = 30 -> d = 10.

![image](https://github.com/user-attachments/assets/09100881-6bf7-4521-ad58-8c8cff0c56d2)
![image](https://github.com/user-attachments/assets/51fbbca4-78d1-40ec-9ef6-d106b16cb9ed)
![image](https://github.com/user-attachments/assets/10acfbc5-b158-44ee-b213-02bb3a1e860b)
![image](https://github.com/user-attachments/assets/5476ec96-11e6-4996-bce3-dc5bde2daafe)
![image](https://github.com/user-attachments/assets/13a5014e-5de7-4147-b605-d4e522313a32)
![image](https://github.com/user-attachments/assets/8d66601a-1e30-4b22-9a63-33ebafa93173)
![image](https://github.com/user-attachments/assets/eafdcf20-1cee-400f-a533-78009b7f448c)
![image](https://github.com/user-attachments/assets/d2ee465f-8bc6-41a1-a30b-824b3e87f3cf)

* 'H' cannot be 4th person can 'H' saw 'YB' at entry and at the 4th person, the entry is 'RB'.
* 'H' cannot be the 2nd person as 'H' saw 'GB' at exit and at the 2nd person, the exit is 'RB'.

![image](https://github.com/user-attachments/assets/86c30778-9585-4f45-9e9d-eac730b88bf9)
![image](https://github.com/user-attachments/assets/32d2f81c-8a1f-46d1-a467-9cd55b8e7599)
![image](https://github.com/user-attachments/assets/9dca715a-1800-4228-ab15-d932897efa40)

* 'P' is not the 2nd person because 'B and G' are adjacent in 2nd person which is not possible in 'P'.
* 'J' is not the 2nd person because the colors are interchanged in 2nd person which is not possible in 'J'. In 'J' there was **no change**.

![image](https://github.com/user-attachments/assets/9f3b2fa4-96d3-46ad-b89e-1f994d6738be)
![image](https://github.com/user-attachments/assets/475ff5ad-2340-4913-bdaf-46b73fa0d339)
![image](https://github.com/user-attachments/assets/46d3af44-f5b9-4020-9a80-05373b4e302e)
![image](https://github.com/user-attachments/assets/4292846d-513e-4321-b378-b9a7fe71f526)
![image](https://github.com/user-attachments/assets/6c39fa10-3828-46f2-8ee0-3a21a0b60e64)

* Case **1**.

![image](https://github.com/user-attachments/assets/27a10a37-c596-4867-b09f-e35735317f55)
![image](https://github.com/user-attachments/assets/cda2fd7e-7de6-4e57-9182-5ea864718703)
![image](https://github.com/user-attachments/assets/46cb761d-85a4-4baf-be8c-74c5953532a5)
![image](https://github.com/user-attachments/assets/86faf828-ddce-4fab-8177-48f8cc6779a8)

* 'Y' is not coming at the 1st place after doing interchange. So Case **1** is wrong/not possible.

![image](https://github.com/user-attachments/assets/61071568-0f3b-4928-8362-70a1c6e84d7e)
![image](https://github.com/user-attachments/assets/c41bb426-92b4-4b1a-a4f3-b5d8c913ebdd)

* Case **2**.

![image](https://github.com/user-attachments/assets/d4c34c13-4afc-419c-9e02-c4f0dc7e0e68)
![image](https://github.com/user-attachments/assets/0a39336a-0df4-43b1-ac39-9417c498dc37)
![image](https://github.com/user-attachments/assets/bcfaf824-fda9-469a-8982-7c10bd0c8ff9)
![image](https://github.com/user-attachments/assets/78ae9a08-705a-4f6e-a5df-17c2703abf1c)
![image](https://github.com/user-attachments/assets/4ca15ae0-7f32-4bf4-9d49-ad1c5ffcdc74)
![image](https://github.com/user-attachments/assets/4855a2b4-bd76-49e5-9e29-c3054ac7ff84)
![image](https://github.com/user-attachments/assets/9d1260d9-2f2f-46a9-a6df-51a11daef6d2)
![image](https://github.com/user-attachments/assets/e326dca1-966f-4452-9178-6448ae0e1f90)
![image](https://github.com/user-attachments/assets/fb1cc934-312a-48c0-a2db-22efa11ae08e)

* 'PR' and 'GB' are together.
* 'G and B' were interchanged by the 2nd person upon **entry**.

![image](https://github.com/user-attachments/assets/1e9d9394-982d-4fe0-8a4c-36bf91f2eb81)
![image](https://github.com/user-attachments/assets/c4235c58-0c27-48a4-b9e9-14fbaaaf1d90)
![image](https://github.com/user-attachments/assets/b1a6270f-0f3e-4c6b-ae26-b3324007d13e)
![image](https://github.com/user-attachments/assets/3c7df693-ade6-4c49-b8a4-a5bbee72835d)
![image](https://github.com/user-attachments/assets/05f2710a-0566-4401-b315-666f06a3f4eb)
![image](https://github.com/user-attachments/assets/bf5d98f6-54ab-4113-9356-f266dc088619)
![image](https://github.com/user-attachments/assets/f59c405d-ea58-4a07-a079-64e6bdd9881b)
![image](https://github.com/user-attachments/assets/bc8de6a5-3f37-4105-b707-18333bb44420)
![image](https://github.com/user-attachments/assets/1f7406b6-2c37-44ae-98d5-a44ee669d058)
![image](https://github.com/user-attachments/assets/df882e0a-e598-4a6a-b59c-0d9b22c00fe4)

For 1st person, 'Y and B' are together.

![image](https://github.com/user-attachments/assets/870d8c9f-7579-4530-bff3-df437f62f6ad)

* Case **1** -> 'B and W' are interchanged.

![image](https://github.com/user-attachments/assets/40ba780c-dd5a-4000-9638-207266a638a5)
![image](https://github.com/user-attachments/assets/a59c8f96-7e29-42a7-b30f-e51abaa774db)

* Case **2** -> 'G and Y' are interchanged.

![image](https://github.com/user-attachments/assets/e04c73c6-a7a4-4246-9a43-fe30d52b39be)

* 'Y' has been moved/interchanged so it cannot be the **answer**.
* Option **C**. [1] [Answer]
* Option **A**. [2] [Answer]
* Either '0' or '1'. Option **D** [3] [Answer]

![image](https://github.com/user-attachments/assets/0f676004-3868-4728-ae58-7c9064ce74e5)
![image](https://github.com/user-attachments/assets/63a974ff-8fdc-4048-a0bd-c42479378ee6)
![image](https://github.com/user-attachments/assets/dbdf9a17-44ff-44cf-832f-88bc03963ddf)

* B -> 5 * 3 + 6 + 6/2 -> 27/23.
* P -> 3 * 5 -> 15.
* W -> Greater than 'P', no point in counting.
* G -> Greater than 'P', no point in counting.
* Option **B**. [4] [Answer]

![image](https://github.com/user-attachments/assets/bda7d721-80f9-4c6d-8ce8-567bbffe12d6)
![image](https://github.com/user-attachments/assets/94fb506a-3c1e-44fd-a410-00f45fa0554a)
![image](https://github.com/user-attachments/assets/a093c96c-be4c-413a-8c52-90a5987115db)

* Maximizing difference -> Maximum - Minimum. [Logic] [Formula]
* Y -> 4 * 1 + 1/5 -> 5/9 -> Minimum.
* B -> 5 * 3 + 6 + 6/2 -> 27/23 -> Maximum.
* Answer -> 18. [5] [Answer]

![image](https://github.com/user-attachments/assets/f588bb1f-32f1-421f-b017-f0d38f10c5b8)
![image](https://github.com/user-attachments/assets/8f532833-4a13-4403-a712-7974850de452)
![image](https://github.com/user-attachments/assets/abf6412b-e07d-42c8-b716-994eb3f7bbfb)
![image](https://github.com/user-attachments/assets/dd98c693-7fd7-48d0-9b57-53d95828332d)
![image](https://github.com/user-attachments/assets/21b1b3d2-fcce-411f-97de-a176d3ef9601)
![image](https://github.com/user-attachments/assets/cd9a41c2-6278-4302-900d-a939524f1985)
![image](https://github.com/user-attachments/assets/bbae45d3-d037-4858-9048-0f9fa2c6a4a3)
![image](https://github.com/user-attachments/assets/9c67d545-7d9c-4e56-be71-5cfaca395324)
![image](https://github.com/user-attachments/assets/df2b51ab-d461-4891-aa27-91a18f9e6641)
![image](https://github.com/user-attachments/assets/fbc2ac7e-98a6-4859-a795-c064b1388b8b)

* 'Bihar' cannot have '3 + 2' because this means that 'Bihar' participants were features in the top '3' in '2' consecutive years. It is done by rajasthan only.
* 'Bihar' -> 5 + 0 -> 0 + 5.

![image](https://github.com/user-attachments/assets/40b22079-8348-4cb7-881d-9f22bb45d717)
![image](https://github.com/user-attachments/assets/b72bc71b-22f7-425f-b2e8-32688ce3fe19)
![image](https://github.com/user-attachments/assets/2bbcc068-6db3-406e-adbb-1002076f88aa)

* 'Gujrat' cannot have '5-3-0' or '3-5-0' because that is done by rajasthan only.
* 2011 already has 1st position for '5L'. So '5-0-3' is not possible.

![image](https://github.com/user-attachments/assets/5e36612a-94b9-4853-9086-322b73dd424d)
![image](https://github.com/user-attachments/assets/f5f7bd95-cf70-483c-b3d0-cc930c28f321)
![image](https://github.com/user-attachments/assets/533baa8f-1e4d-4a58-9591-bb653bec7c51)

* 'MP' is having many cases so we will hold it for now.

![image](https://github.com/user-attachments/assets/a6a50660-893a-428e-925f-ca720f261d41)
![image](https://github.com/user-attachments/assets/acb33865-66f6-4c55-8b07-39234293d930)
![image](https://github.com/user-attachments/assets/17ea81ab-c9cc-49be-8c0b-33d63c7dd370)
![image](https://github.com/user-attachments/assets/e2d4ef71-3cb2-4b20-8dab-ae1c8657883e)
![image](https://github.com/user-attachments/assets/8640eaac-2692-45d5-aa3d-ea94240907e1)
![image](https://github.com/user-attachments/assets/b7c80b59-db9e-444f-8a25-455710f8146b)

* Only '0' was left in '2011' so 'karnataka' took '0' in '2011'.

![image](https://github.com/user-attachments/assets/3cf33895-041f-4436-a5bd-e1ffcb6d6ae2)

* 'Maharashtra' in '2013' is '0' for sure.

![image](https://github.com/user-attachments/assets/4c6856b9-6319-4730-b648-940de940fdb4)
![image](https://github.com/user-attachments/assets/2a17ae73-081a-457d-b146-2bae3eb353c8)

* 'Punjab' in '2014' is '0' for sure.

![image](https://github.com/user-attachments/assets/0509b67a-eaa8-421b-b61f-fb37406a6a0e)
![image](https://github.com/user-attachments/assets/c065bcef-6d9a-4c44-9cba-20fce2e0b55e)
![image](https://github.com/user-attachments/assets/c06b5314-8454-48de-ac03-1bb3b66fed11)
![image](https://github.com/user-attachments/assets/725e3560-1652-4b78-85da-8efa814f3f2a)

* '2014' is left with '3L' only. So 'Maharashtra' in '2014' is '3L'.

![image](https://github.com/user-attachments/assets/81dcc68f-b0be-4672-b8a6-985d4532373c)

* 'MP and Punjap' in '2013 and 2015' can shuffle amongst them.

![image](https://github.com/user-attachments/assets/dc1315e5-cd3a-4081-8703-abbca219f7bb)

* Answers.

![image](https://github.com/user-attachments/assets/fdc6d3b5-0251-411f-963b-3774d9fa29d3)
![image](https://github.com/user-attachments/assets/9c581b84-4d24-4c1d-80b8-7a322f40d67e)
![image](https://github.com/user-attachments/assets/e7a558fe-a3de-4914-afc6-6325cab9d397)
![image](https://github.com/user-attachments/assets/b4ed2bdf-e6d6-40a2-9032-d2b716c354bd)
![image](https://github.com/user-attachments/assets/472c7835-7585-4668-b10d-a395178894cb)

* We are trying to do the extreme cases first.

![image](https://github.com/user-attachments/assets/58c90e88-5668-4e83-8509-19376f0e5795)

* We have already played '1' match against 'CC'. We cannot play another.

![image](https://github.com/user-attachments/assets/eb87fcb2-cfa5-4343-80b8-51cc2cd46068)
![image](https://github.com/user-attachments/assets/4e94adb8-9935-4985-afab-d18772e5c543)

* 'AA' cannot win with '0' goals.
* '0' goals will come in draw.

![image](https://github.com/user-attachments/assets/76765409-bf90-430d-853e-4be8c3c32582)
![image](https://github.com/user-attachments/assets/092c4ac1-e51c-40f6-992a-707a5f52af2d)
![image](https://github.com/user-attachments/assets/17e74c8f-788a-4aee-b66d-dc828f31c1c5)

* 'BB' have already played '1' match against 'CC'. We cannot play another. So '6' in 'CC' is not possible.

![image](https://github.com/user-attachments/assets/9a422fe9-45b7-4801-873b-da2f9f948e4b)
![image](https://github.com/user-attachments/assets/e216bca9-8ceb-423c-a8c2-a500252446ec)
![image](https://github.com/user-attachments/assets/e406fd73-b4ae-48b7-945e-1cb3390f2e95)
![image](https://github.com/user-attachments/assets/22880960-a3f7-4e91-84a4-fd8b22c6c615)

* Answer.

![image](https://github.com/user-attachments/assets/91a9d389-c00f-4c5f-82b9-914edd2fd3da)
![image](https://github.com/user-attachments/assets/a1e09c7e-ecb1-48e4-96d9-9dd1b47dae52)
![image](https://github.com/user-attachments/assets/dd314149-fa18-4a8e-826d-5c3e12c706d9)
![image](https://github.com/user-attachments/assets/849cb8a6-b74a-4aba-b9a0-3310c4d383d8)

* x + 2x -> 3x.
* Don't limit it for now.

![image](https://github.com/user-attachments/assets/9130c6b0-357f-430c-8b14-a8218b785aff)

* Total shouldn't have unique values.

![image](https://github.com/user-attachments/assets/b14a6189-c992-438d-84d2-0016349232af)
![image](https://github.com/user-attachments/assets/5e02368f-16f0-4fc9-bdc4-12235b5ac327)

* Range is from '12 to 19'.

![image](https://github.com/user-attachments/assets/3fb69353-08ae-4634-82b3-85b737e37ec4)
![image](https://github.com/user-attachments/assets/60b688fe-cb4a-4a6e-a783-6aa8c069da7d)

* '13' combo is not possible.
* Next combo -> 3 + 4 + 7 -> 14.
* We got unique in '14' but we don't want unique. So it is not possible.
* We got unique in '15' but we don't want unique. So it is not possible.

![image](https://github.com/user-attachments/assets/24139345-45dd-4263-9c28-979085172f48)
![image](https://github.com/user-attachments/assets/d9f8559f-b009-4aa4-a499-1a03f226cc1e)

* We are getting different combos but we are still able to uniquely state the value of 'A' which is '3'. So it is not possible.

![image](https://github.com/user-attachments/assets/d445f1c3-e57c-4f5c-a10e-ced253fe4541)
![image](https://github.com/user-attachments/assets/b6623275-9c23-415e-8bf0-649eaa3a7382)

* We are getting different combos but we are still able to uniquely state the value of 'A' which is '6'. So it is not possible.

![image](https://github.com/user-attachments/assets/9dfe1c52-55d9-4a78-b1b2-f2ca223aa9dd)
![image](https://github.com/user-attachments/assets/8b6b7505-2eef-4c2b-a1e9-17302916acef)

* B > 5 -> B = 8 case -> C = 7 -> 2 + 5 -> Girls in 'C' -> 2. [2]

![image](https://github.com/user-attachments/assets/f8acfc8c-3d93-4213-a323-46c91431c2da)
![image](https://github.com/user-attachments/assets/5d0a48c3-9445-4d18-952b-92916e868fda)

* [3]

![image](https://github.com/user-attachments/assets/918db546-2e33-459b-8f36-55d393dec06b)
![image](https://github.com/user-attachments/assets/bfd63563-09e2-40fd-b7b3-c7ad92293862)

* [4]

![image](https://github.com/user-attachments/assets/e04425a6-a459-4810-af31-622bd4dadf20)

* Answers.

![image](https://github.com/user-attachments/assets/87883294-efc1-44bd-8d97-7b6a4bce89c5)
![image](https://github.com/user-attachments/assets/537a7231-5906-4a08-8dbc-3372570063e9)

* This is not possible.

![image](https://github.com/user-attachments/assets/da51f27c-0423-47ed-a32f-4eef94344378)

* We are anyways not using all of the prices. This is not possible.

![image](https://github.com/user-attachments/assets/5bb1be77-e49b-4aa9-9a58-8ceece2ba174)
![image](https://github.com/user-attachments/assets/03039114-cfef-41c5-8e75-f3cbf1d46ac6)
![image](https://github.com/user-attachments/assets/c5068193-a0d9-46cb-973d-36060b06b480)
![image](https://github.com/user-attachments/assets/f1540309-b5b9-42da-bbf1-edf09f3fa470)
![image](https://github.com/user-attachments/assets/c00c3d98-b8c0-4584-bbff-69bde64d583f)
![image](https://github.com/user-attachments/assets/00435419-6622-4770-acb8-c94c6d3a2a2f)
![image](https://github.com/user-attachments/assets/a866f036-491f-497c-b257-fbdc4a78fe10)
![image](https://github.com/user-attachments/assets/3182d243-f392-4d43-851d-6a85dff56898)
![image](https://github.com/user-attachments/assets/687f549a-bb92-4db1-b32a-a8c9d4ff146a)

* 4x + 5x -> 9x.
* a + 40 = 5x + 5 -> 5x - 35.

![image](https://github.com/user-attachments/assets/67f7a528-b97d-4810-9f76-d018c9854b5a)
![image](https://github.com/user-attachments/assets/e62d7bea-4a28-4f92-8e60-1ab038c935fe)
![image](https://github.com/user-attachments/assets/365ffc53-2e5d-40e0-aa1c-7db0f1c753b7)

* We are attacking profit because profit of day '3' is given.

![image](https://github.com/user-attachments/assets/a965b5fe-6aae-449c-88e0-bf245c057158)
![image](https://github.com/user-attachments/assets/320c20da-4dea-4092-9d28-2ddfd9a2c6c9)

* 7 < x <= 11.

![image](https://github.com/user-attachments/assets/9bda8b3f-104f-474e-8b9b-d8a14c311b18)
![image](https://github.com/user-attachments/assets/35d48c96-eabf-419c-aef0-24abed528c41)

* All of the questions are definite questions only. None of them are indefinite questions. One of the cases will come as answer only. Other case will get eliminated.

![image](https://github.com/user-attachments/assets/006806e4-f5ff-4688-bb70-2c9097eb1dc3)
![image](https://github.com/user-attachments/assets/279ed1bf-c914-49eb-bb0d-737f9120dbdc)

* 52 - 36 -> 16.

![image](https://github.com/user-attachments/assets/3bd6885b-d99c-4402-a72d-afd3e2a5a52b)
![image](https://github.com/user-attachments/assets/b466f61f-2d7b-4acb-9b59-9cf890d2bb2a)
![image](https://github.com/user-attachments/assets/78f7b855-99f7-42d8-b7f5-3c072f6980e7)
![image](https://github.com/user-attachments/assets/c37b64f6-ab4f-4c60-bda4-6c1a69d3bb93)

* '7' is not a multiple of '790'. This case is not possible.

![image](https://github.com/user-attachments/assets/7d853d9e-ffe6-435f-ba5e-010fe19b0b70)
![image](https://github.com/user-attachments/assets/b1824c2d-8d79-4c23-9aaf-84d3128930af)
![image](https://github.com/user-attachments/assets/b73bce8d-ae4d-4ca0-8fdb-10a6e375aa0f)
![image](https://github.com/user-attachments/assets/dcef63bb-b8f4-481d-80b9-8c57dede5f75)
![image](https://github.com/user-attachments/assets/5b05448c-e507-46d6-9def-080962cb50aa)

* x = 8
* 5x - 35 -> 5.
* 5 * 19 -> 95

![image](https://github.com/user-attachments/assets/fbe738b5-1c3e-4357-951f-85ac6674492c)
![image](https://github.com/user-attachments/assets/148f6bfc-1c6d-4e92-97d9-93d4bd687176)
![image](https://github.com/user-attachments/assets/80b39e67-1c55-4389-bc1b-ace3607a2b15)

* b -> 91 + 5 -> 96L.

![image](https://github.com/user-attachments/assets/e618c7b4-7d61-4cf6-8769-54d0e940f25a)
![image](https://github.com/user-attachments/assets/3b6d0c02-ed6f-411e-b753-2fe039eab615)

* 96 - 40 -> 56.

![image](https://github.com/user-attachments/assets/e1ececfe-7a24-4713-a733-006fee4aa120)
![image](https://github.com/user-attachments/assets/fec3d126-016f-442d-a254-9ab04dc9bf9c)
![image](https://github.com/user-attachments/assets/61691707-4d1b-4e3d-a7d6-51a25acdafc4)
![image](https://github.com/user-attachments/assets/195f1033-d7d4-4902-8d39-423807d8cb3b)
![image](https://github.com/user-attachments/assets/1cfe0dfb-f390-433c-a54e-fbb664117dde)
![image](https://github.com/user-attachments/assets/73a6b0c2-7f33-44ef-b784-3c1580f32747)
![image](https://github.com/user-attachments/assets/35c52d7b-46bc-42ae-aa4b-2589b3b0f192)
![image](https://github.com/user-attachments/assets/1a7cda31-ada6-488b-a9c2-2e0de2a269c1)
![image](https://github.com/user-attachments/assets/5a4f2901-2953-4c66-9bbf-c27885a71d97)
![image](https://github.com/user-attachments/assets/57c3bea6-0339-4d66-9541-0c049f958f76)
![image](https://github.com/user-attachments/assets/42d2cf33-2d03-497c-b175-4cd3a2c05ebb)
![image](https://github.com/user-attachments/assets/98ee99d7-65b2-4002-951f-59269cce00b2)

* 73 - 69 -> 4.

![image](https://github.com/user-attachments/assets/2c823275-77d1-4f2a-b5f4-0c0189bd366b)

* 45 - (12 + 10) -> 23 -> f -> Eaten all '6' chocolates.
 
![image](https://github.com/user-attachments/assets/0c56e61c-3760-44d6-b343-4e35653d5be3)

* 23 -> It also had eaten 'F' chocolates also.

![image](https://github.com/user-attachments/assets/5e67f40b-6155-4f1a-8e44-a05bf9c78ffa)
![image](https://github.com/user-attachments/assets/b15d234e-3607-4ea4-9e3f-e945b7036bf4)
![image](https://github.com/user-attachments/assets/18ace642-4217-4c26-b986-3b8bb68c654b)

* Answer.

![image](https://github.com/user-attachments/assets/cc07ec2b-7dac-4ddf-935a-5cba588dbde3)
![image](https://github.com/user-attachments/assets/45307f26-6206-4945-bc09-e3a94858ac5e)
![image](https://github.com/user-attachments/assets/20231a39-0b40-4955-a028-8c285320a371)

* 348 - 263 -> 85. [Method **1**]

![image](https://github.com/user-attachments/assets/ad4de236-6531-4bec-8318-e7c5104782b3)

* 100 - 48 -> 52% -> They are not playing '1' of the sports.
* 52 - 37 -> 15%.
* 100 - 15 -> 85%. [Method **2**]

![image](https://github.com/user-attachments/assets/79918bb3-2908-44a6-a764-2db8f62eb258)
![image](https://github.com/user-attachments/assets/b3c9662a-6945-4b56-b784-00cda8cdaa16)
![image](https://github.com/user-attachments/assets/4674cba1-0ec7-43c4-a97f-86c4b488b44a)
![image](https://github.com/user-attachments/assets/6cbc9f1d-5952-4805-ad72-ea0e29a4d6b0)
![image](https://github.com/user-attachments/assets/011d1f23-3860-4f5c-8d6a-b59a9045c134)
![image](https://github.com/user-attachments/assets/daa39ba6-8a6f-4943-8718-775de71fde14)

* 'b' is greater than 'c'.

![image](https://github.com/user-attachments/assets/bd59f6c3-5ee8-4c2b-bef9-12dd7091be41)
![image](https://github.com/user-attachments/assets/fef721e8-74f3-442a-9a84-62a4ad0a2b78)
![image](https://github.com/user-attachments/assets/7dd960ae-ddbe-472c-a957-3fdfb5b3ba4f)
![image](https://github.com/user-attachments/assets/59d473ea-c4d5-4e5b-a392-7c331a84713a)
![image](https://github.com/user-attachments/assets/a9b4de6f-99a7-498f-b4be-d39d63440472)
![image](https://github.com/user-attachments/assets/f4927729-40b9-48b1-a3c7-e863489405c1)
![image](https://github.com/user-attachments/assets/da8052ac-c343-4f8f-b704-9f69895fd998)

* This is not needed.

![image](https://github.com/user-attachments/assets/5e9f36aa-e59c-46a7-a049-17ff442d1fe4)
![image](https://github.com/user-attachments/assets/0db4a017-2db0-4378-98c4-9a8086183c85)
![image](https://github.com/user-attachments/assets/2515d937-3f0d-4eea-9bbe-f09329db44b4)
![image](https://github.com/user-attachments/assets/2f4aadb9-19cf-4936-a984-a0a679869009)

* 'g' is a bigger no. compared to others.

![image](https://github.com/user-attachments/assets/73e7c81e-0889-48fa-aa92-00b3d5a35efc)
![image](https://github.com/user-attachments/assets/58baf8d6-cf76-4c94-ab31-0a12d4be2e2a)
![image](https://github.com/user-attachments/assets/73ad73e9-cbf3-407d-bb8c-779c09e954df)
![image](https://github.com/user-attachments/assets/19fc22a3-dbe4-4831-a06b-d64da3e50f00)
![image](https://github.com/user-attachments/assets/bab9ad59-9ff2-4028-99d3-b80b6c7e1e6b)
![image](https://github.com/user-attachments/assets/901707c8-19f1-4439-93e5-066fc209584a)
![image](https://github.com/user-attachments/assets/1c8d4aab-8a37-497c-9d90-63ed0c8d1ff5)
![image](https://github.com/user-attachments/assets/439c29f8-0005-470d-b8a8-aeb7d2688da5)
![image](https://github.com/user-attachments/assets/34db436b-870f-4948-b50d-2ea94b1d1dea)

* 40/16 -> Will not been an integer.

![image](https://github.com/user-attachments/assets/f9ca8d55-4802-476f-8e13-50c6c23555ac)

* Common/Multiple between '8 and 14' -> 2.
* We can put '2' in the rest of them as well.

![image](https://github.com/user-attachments/assets/042094d0-764a-43cb-a100-7b5efb4cdf82)
![image](https://github.com/user-attachments/assets/e194e912-ed8a-4e4a-b90e-98786f22fdad)

* 64/(5/4) -> Not integer -> not possible.

![image](https://github.com/user-attachments/assets/ae3d6784-bd5f-4a5f-990d-fc74efe732bf)
![image](https://github.com/user-attachments/assets/8bfdcc10-83e4-42e7-8eb8-561ba5934d8b)
![image](https://github.com/user-attachments/assets/63cff69d-f086-4f4f-a455-36505093fd02)
![image](https://github.com/user-attachments/assets/1fe1977e-1e9e-4e8d-b8b9-84e053ccaee9)
![image](https://github.com/user-attachments/assets/ed1ee528-fb04-43db-89bc-c954e3bce32e)
![image](https://github.com/user-attachments/assets/0c33057b-a196-494e-85f7-0efaf02e1cc2)
![image](https://github.com/user-attachments/assets/17efb733-fd1c-4640-87df-f6420371b999)
![image](https://github.com/user-attachments/assets/9b24d07c-e8f8-4007-9f86-964a84009562)
![image](https://github.com/user-attachments/assets/8a5412bf-2a2a-4f6f-965e-a7a887236e91)
![image](https://github.com/user-attachments/assets/c03f5e4b-2c3a-4d2f-89e1-3eca091135b4)
![image](https://github.com/user-attachments/assets/dc5cfc65-cf61-4a52-a8db-1c6a4bcd3a77)
![image](https://github.com/user-attachments/assets/6a5b2209-168e-454f-a519-bf0597915360)
![image](https://github.com/user-attachments/assets/74b3afc7-db03-4625-8214-d7426d3a06ca)
![image](https://github.com/user-attachments/assets/f3555cf5-9626-4e6f-98da-52f960956505)
![image](https://github.com/user-attachments/assets/e7ba3fae-526a-4c88-94f0-75e2943880e2)
![image](https://github.com/user-attachments/assets/8d038eb6-6f5d-481b-b143-8c5b6092cb6c)
![image](https://github.com/user-attachments/assets/25694284-1462-4a23-a9e5-2480f3ee8f8c)
![image](https://github.com/user-attachments/assets/875720b1-5afe-4588-92c4-168364b62793)
![image](https://github.com/user-attachments/assets/79a670c0-7fe2-4179-8782-914cf3bd93d0)
![image](https://github.com/user-attachments/assets/e2e151c4-431f-445b-bd35-47d82be46f58)
![image](https://github.com/user-attachments/assets/de4f4c6e-270a-4b18-8935-704d5b05b9e2)
![image](https://github.com/user-attachments/assets/6e5da8dc-5721-48bb-b2ad-74f073a1e8a7)
![image](https://github.com/user-attachments/assets/47553259-2f49-4a6f-b6ef-ab215cb7c1f3)
![image](https://github.com/user-attachments/assets/52ad7803-0f1c-459d-aa67-7c99a23c36bf)
![image](https://github.com/user-attachments/assets/877f07b2-f9a2-4d85-916c-c9e63a982522)
![image](https://github.com/user-attachments/assets/f9faf785-7235-426c-a016-971a81137bcf)
![image](https://github.com/user-attachments/assets/e2fb1701-3e87-47da-b28b-13439c569052)
![image](https://github.com/user-attachments/assets/d4435678-27d9-49d1-aeab-3f8d847df7d2)
![image](https://github.com/user-attachments/assets/567b842c-7da2-4799-8f6e-c3d65a4efbc2)
![image](https://github.com/user-attachments/assets/c4189bb3-79e9-470a-a576-223232a0252e)
![image](https://github.com/user-attachments/assets/76626f6b-1875-46e4-81e9-6b7cd91050db)
![image](https://github.com/user-attachments/assets/2d569c2b-ab12-45f1-9864-ddb0a629885b)
![image](https://github.com/user-attachments/assets/64f567ef-37b8-4ccd-8d9e-8df4d28ea4df)
![image](https://github.com/user-attachments/assets/2c691a47-16df-4464-abdc-9d2598fcb8ca)
![image](https://github.com/user-attachments/assets/17b08953-d320-4d16-9bf1-fcbde1e7e83d)
![image](https://github.com/user-attachments/assets/f9577f16-0131-4dca-bf3f-54b748fba511)
![image](https://github.com/user-attachments/assets/5b51fd58-9441-41e5-a3d9-eba40a482549)
![image](https://github.com/user-attachments/assets/698a89b0-4f57-4a63-9b6f-34a2abde5917)
![image](https://github.com/user-attachments/assets/3f38b18c-a4f7-48ac-bb6f-07b96cf49e6f)
![image](https://github.com/user-attachments/assets/d87e0270-dbdc-4290-acf0-ced9cce3d6e5)
![image](https://github.com/user-attachments/assets/6941b121-6816-4bd6-9c6c-f35bf04ecdd6)
![image](https://github.com/user-attachments/assets/5a06b0e8-0e80-4935-af64-3a99e57ef67c)
![image](https://github.com/user-attachments/assets/f5fc47fd-5338-4924-985a-d5941cc1c93b)
![image](https://github.com/user-attachments/assets/545e74a8-b7f9-4bb6-88af-da573a81d93b)
![image](https://github.com/user-attachments/assets/43e7bf8e-32a7-4199-b970-eaa0a2fa8c37)
![image](https://github.com/user-attachments/assets/727da608-6c82-4309-aa4d-3424de13c3c6)

* 26 - 16 -> 10.
* 28 - 16 -> 12.

![image](https://github.com/user-attachments/assets/62560837-3c60-421a-95c9-51c1157a408b)

* We want to maximize 'B and D'.
* 37 - 22 -> 15.
* We have to leave 'B and D' to the end.

![image](https://github.com/user-attachments/assets/5639d507-af72-4deb-b192-8fce1eca3d66)
![image](https://github.com/user-attachments/assets/579868b0-701c-46a4-b2bd-39d31185332c)

* 25 - (10 + 12) -> 3.
* We have to balance the remaining '3' in 'A'.
* 24 - 3 -> 21.
* 15 + 21 -> 36.

![image](https://github.com/user-attachments/assets/1e6d234a-7946-4d5c-88c5-cfc3f1900cce)
![image](https://github.com/user-attachments/assets/d85c9aa0-4a98-47a9-a253-08edd5900f57)

* Answer -> 21. [1]
* Whoever we want to maximize, we have to hold it till the end. [Logic] [Concept]

![image](https://github.com/user-attachments/assets/41e9cf73-f41e-44d5-93f4-05fbfc275939)
![image](https://github.com/user-attachments/assets/5a6fe4fe-ee05-48a2-b2e6-8c73d57b23bf)
![image](https://github.com/user-attachments/assets/f5686704-66f9-40cf-8210-93941b0f1f6f)

* We have to check both 'A won to B' and 'A lost to B'.

![image](https://github.com/user-attachments/assets/4b1691d0-23cd-458b-a11e-7f19ea30c317)
![image](https://github.com/user-attachments/assets/8113e4bb-ab51-44d3-b120-afcde44cff0e)
![image](https://github.com/user-attachments/assets/c5349971-2169-4ff7-a1e3-08f8b9420155)

* 'A' lost '2' extra times either against 'C or D'. 'A' fought others also other than 'B'. 'A' is loosing more than 'B' is winning.  So 'AB' is not possible

![image](https://github.com/user-attachments/assets/644cc223-2f82-46a2-97ca-014d77614d12)
![image](https://github.com/user-attachments/assets/ea5d9071-f8d3-493a-9fb5-d188cf8f2546)

* 'A' won -> A < B.
* 'A' lost -> A < B.

![image](https://github.com/user-attachments/assets/4897a652-f8e5-414b-9815-bd8c2d9c3c05)
![image](https://github.com/user-attachments/assets/f9d165f3-6e04-4aee-a7e6-f4f428346f83)
![image](https://github.com/user-attachments/assets/b00d7e48-57c6-467f-9c9d-881d66cba6e4)

* 'D' won -> D < A -> 33 < 38.
* 'D' lost -> D < A -> 24 < 25.
* So 'DA' is possible.


* 'C' won -> C < B -> 22 < 26.
* 'C' lost -> C < B -> 28 < 36.
* So 'CB' is possible.

![image](https://github.com/user-attachments/assets/5aa3744e-ba93-4e23-ac68-0f53dd391138)
![image](https://github.com/user-attachments/assets/e8806c4e-9bbf-45dd-8eab-185ecf380009)

* So 'CD' is possible.
* This is **Step '1'**.

![image](https://github.com/user-attachments/assets/1caf1e8e-2e7e-4bac-9f46-b177eff0d45b)
![image](https://github.com/user-attachments/assets/475d9351-a02b-4665-aad0-6f44ee0a6bec)

* Everyone ordered only '1' dish. Nobody ordered '2' dishes.
* Every dish ordered by '1' person.

![image](https://github.com/user-attachments/assets/5ab1a900-7b24-44cf-9620-81324c7bac3b)
![image](https://github.com/user-attachments/assets/6fdffec7-78b7-4e4c-9ae2-18915da2ca83)
![image](https://github.com/user-attachments/assets/00f72999-eb79-4577-8a17-39726a8fc420)
![image](https://github.com/user-attachments/assets/90376bed-122b-447d-9626-bb2a1b8ca302)
![image](https://github.com/user-attachments/assets/a1eeba56-ac38-4bee-bbc8-df57b9084dd6)
![image](https://github.com/user-attachments/assets/5c53eadb-e4a2-4b67-bb02-153f65158628)
![image](https://github.com/user-attachments/assets/bd8cfe83-7a31-44e6-9da9-3928fd30dc03)
![image](https://github.com/user-attachments/assets/8b53b4ad-5014-4901-89da-c50df98cccdd)
![image](https://github.com/user-attachments/assets/c09cae70-2b1c-49d2-8836-3d91a1 ca0c31)
![image](https://github.com/user-attachments/assets/80751280-bc40-4181-b8e1-77c7da54e686)

* 450 has been written twice(2), so it will be ordered twice(2) also which is done by 'A and G'.

![image](https://github.com/user-attachments/assets/4fb4b4a3-74c8-4ab4-a6f8-178ea11dad3c)
![image](https://github.com/user-attachments/assets/0624ed9f-8257-4644-9cdd-9dd338547fcb)
![image](https://github.com/user-attachments/assets/b47be4ca-9022-4ed2-a614-13654ec3073e)
![image](https://github.com/user-attachments/assets/c0704789-ae41-4f30-9da8-90d954d4a06b)
![image](https://github.com/user-attachments/assets/724d427a-b1a2-438a-9502-63552ee1212b)

* Answers.

![image](https://github.com/user-attachments/assets/9ceec9be-df6b-4ca8-a69e-6611eacb02bf)
![image](https://github.com/user-attachments/assets/78bd3ef1-261d-440b-aeb6-fc8d65902bb6)
![image](https://github.com/user-attachments/assets/c8ae0a9e-e2fa-4fd7-bc68-f51c773fae84)
![image](https://github.com/user-attachments/assets/2ce4dbd1-d87e-4e8c-a06b-1837a01c8d0d)
![image](https://github.com/user-attachments/assets/82d7e6e9-73a6-4dbf-82bb-803047135e4d)
![image](https://github.com/user-attachments/assets/6fe8cdfb-f612-47b9-854d-f376056aa485)
![image](https://github.com/user-attachments/assets/5cf942d8-069e-427f-a49f-07cbf652611a)
![image](https://github.com/user-attachments/assets/e70925d4-5308-4053-8322-c25e79ee6c09)
![image](https://github.com/user-attachments/assets/e8adadf4-cec2-4916-9ff8-1ca764c185a5)
![image](https://github.com/user-attachments/assets/5c706cd7-a3b8-4fcc-85c1-d15a1efafd7b)
![image](https://github.com/user-attachments/assets/724e89db-5b8e-4d7e-bb42-0ac433c83dc5)

* B = 1KM/hr. [Let]

![image](https://github.com/user-attachments/assets/5dff3d9a-872f-4412-a237-8ff60e19207a)
![image](https://github.com/user-attachments/assets/a12bb4a6-7d09-4790-9bd7-9d241245308a)
![image](https://github.com/user-attachments/assets/6ec4dbc5-e865-49e0-9b68-813d610906bc)
![image](https://github.com/user-attachments/assets/d76f2cbc-ebaa-4592-bd99-48cfaeb2c9f8)
![image](https://github.com/user-attachments/assets/6b846c35-f68a-4952-b9cc-1aa02e4158f5)
![image](https://github.com/user-attachments/assets/ba2c0b15-1d15-49d0-969a-57984b00f1a8)
![image](https://github.com/user-attachments/assets/67c0191e-d44c-449f-8b7f-f1f28a72222a)
![image](https://github.com/user-attachments/assets/2c5b6cc6-0e60-4a82-8669-b3821f0d827f)

### Sectionals

#### 9

![image](https://github.com/user-attachments/assets/816ffe0d-defc-48f6-b469-1c85c52c9c0d)
![image](https://github.com/user-attachments/assets/ffc2876e-1ad3-4e41-8bf1-a33968395e72)
![image](https://github.com/user-attachments/assets/de66dd03-7985-489b-83b3-4545957ca67d)
![image](https://github.com/user-attachments/assets/62d7f0d7-c575-41f0-bea6-951952d4d109)

* 16.66% -> 1/6.

![image](https://github.com/user-attachments/assets/303fcdee-1812-4178-a31f-595a74f24950)
![image](https://github.com/user-attachments/assets/dc1187e7-bb4e-486f-b3c2-9a30bee4aaab)
![image](https://github.com/user-attachments/assets/2486d5e7-e47c-40d8-b045-d7b94392b5a1)
![image](https://github.com/user-attachments/assets/d28ebc1e-e121-4066-bf2f-e2e4f60e8734)
![image](https://github.com/user-attachments/assets/cb3290be-f333-496c-a4b1-58b84bfb5d3c)
![image](https://github.com/user-attachments/assets/d741c52f-e907-4906-a386-196ce8147a1f)

* Multiplying entire row and column with '3'.

![image](https://github.com/user-attachments/assets/102887a2-5921-4ed8-9001-f7ff71a68400)
![image](https://github.com/user-attachments/assets/9f7a83f2-d7b7-41ce-84c2-7365289b71d6)

* 270 * 1/6 -> 45x.

![image](https://github.com/user-attachments/assets/669e3778-8a9d-4ea3-aeee-6e0a0395b5f0)
![image](https://github.com/user-attachments/assets/9e3de403-a9ca-48ff-9c28-a51feb63b823)
![image](https://github.com/user-attachments/assets/40e276c5-e3d4-44ac-8aa7-65399747d550)
![image](https://github.com/user-attachments/assets/5e93ddee-697e-40ee-ad25-c57e08be588f)
![image](https://github.com/user-attachments/assets/3ae713d1-65d7-4136-b1d4-b950b4bcd205)
![image](https://github.com/user-attachments/assets/ff1aff96-d086-4503-84c0-5930c4b49a2a)
![image](https://github.com/user-attachments/assets/7852fa5c-a54d-46c9-bce8-d26a7bb0b96d)
![image](https://github.com/user-attachments/assets/8a7cde8c-d4e9-4670-839f-7c8ba1aa3f00)

* Both the tables are representing same group of people.
* Not Incorrect -> True(T).
* False(F).

![image](https://github.com/user-attachments/assets/c7a03475-f705-41dc-b24c-e998af7db493)

* x = 2/3 -> No. of people cannot be in **fractions** -> This is **not possible**.

![image](https://github.com/user-attachments/assets/6ba95331-aa7f-4cbc-8d67-fac1b5d06cf9)
![image](https://github.com/user-attachments/assets/fd91ada4-daea-4f11-a88e-ba6d0a2d840c)
![image](https://github.com/user-attachments/assets/27a61a06-0dd7-4732-9a0e-5080b2de13d1)
![image](https://github.com/user-attachments/assets/0673ab5e-6dae-4846-a99c-707bb375e01c)
![image](https://github.com/user-attachments/assets/659f2daf-9276-43ce-91e7-fc586af8facf)

* All the nos. are multiple of '5'. 

![image](https://github.com/user-attachments/assets/befc8f09-533b-4c7d-9f94-d109d94e2d3f)
![image](https://github.com/user-attachments/assets/0c435b6f-6614-427d-a432-1cfb80e84418)
![image](https://github.com/user-attachments/assets/f0d2f776-718e-4941-a413-0ffaeddb467b)

* Definitely incorrect -> 100% false, not possible/possibility.

![image](https://github.com/user-attachments/assets/1f1cb2f2-a2da-43dd-9fa8-b93e0a840229)
![image](https://github.com/user-attachments/assets/2e555705-2bb4-4062-8382-976440a1130a)
![image](https://github.com/user-attachments/assets/5d1b55eb-08c9-46e0-8d66-46c7979303dd)
![image](https://github.com/user-attachments/assets/3ffb3e3b-6500-450f-b0d7-f5665e0a08d1)











































































































































































































































































































































































































 














































 













 




























































































































## IMPORTANT

![image](https://github.com/user-attachments/assets/6a1b32e0-525b-419d-ac07-986e343d22a2)
![image](https://github.com/user-attachments/assets/13e59607-4f9e-4367-918c-60e6fb1a5e6f)
![image](https://github.com/user-attachments/assets/ae4808b5-e055-455e-8b44-fc13bb41bc72)


## Misc

![image](https://github.com/user-attachments/assets/5e53bb14-28f4-40a5-997b-727b1a446994)
![image](https://github.com/user-attachments/assets/173d9ae3-eb6e-4b07-9a45-849fed0ac976)
![image](https://github.com/user-attachments/assets/77884239-d787-40a3-921a-09042246d13f)
![image](https://github.com/user-attachments/assets/723d1fd2-a7cd-4559-8365-5ccee4fe13cb)
![image](https://github.com/user-attachments/assets/1011dc12-f9a8-49bc-b48b-b9137978caf2)
![image](https://github.com/user-attachments/assets/2b1b4f89-d9a6-405f-8ea8-0eaa041ebab2)
![image](https://github.com/user-attachments/assets/08c7561b-6715-4622-af12-8af32f337a87)
