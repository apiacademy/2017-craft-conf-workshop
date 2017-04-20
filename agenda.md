# Hypermedia Hacking Workshop (2017)

## One Day Workshop Agenda 

### Morning Session -- From Zero to Links

#### 1. What is Hypermedia and Why Use it? (30min)
Students will learn the basics of the hypermedia style API and the ten H-Factors used to create hypermedia APIs.

 * The Hypermedia Basics (10min)
 * H-Factors (5min)
 * Quick Quiz: "Where's the H-Factor?" (5min)
 * Group Discussion: "Hypermedia Advantages and Drawbacks" (10min)

#### 2, The Plain JSON Client (35min)
The classic CRUD (Create-Read-Update-Delete) pattern is reviewed. Students will install and test run the provided CRUD client as a way to confirm their setup for the rest of the class.

 * The CRUD Pattern (10min)
 * Exercise: Install/Run Client (15min)
 * Group Discussion: "Where does CRUD Fall Short?" (10min)

#### 3. Plain JSON and Change (35)
The backend API changes and now the client app is "broken." Students will fix the CRUD client and review the OAA (Object-Address-Actions) challenge for future lessons.

 * When you add a field: EmailField (10min)
 * Exercise: Email Support (15min)
 * The OAA Challenge (10min)


#### 4. The JSON Link Client (35min)
The first hypermedia-style client (Link Client) is introduced. Students will update their JSON client to be able to consume links instead of construct them.

 * Describing Links (Addresses) (10)
 * Exercise: Consuming Links (15)
 * Group Discussion: "Why not stop here?" (10min)


#### 5. The Link Client and Change (35min)
Now, with the new Link Client, we'll introduce a new action (MarkComplete) to the API. Students will see what, if anything, breaks now and what it takes to fix this updated client.

 * Adding the MarkComplete Action (10min)
 * Exercise: Including MarkComplete Support (15min)
 * Group Discussion: "When is the HAL Media Type a good fit?" (10min)

### LUNCH

### Afternoon Session -- From Templates to Profiles

#### 6. The JSON Template Client (35min)
The second hypermedia-style client can handle templates (forms). Students will update their Link Client to be able to consume forms instead of using internal hard-coded actions.

 * Describing Actions (Templates) (10min)
 * Exercise: Including Templates (20min)
 * Quick Quiz: "Is this a Template?" (5min)

#### 7. The JSON Template Client and Change (35min)
With the new Template Client running, we'll introduce another change (TagField) to the API and see if anything breaks and how to fix it.

 * Adding the TagField (10)
 * Exercise: Including TagField Support (15min)
 * Group Discussion: "What does the Siren Media Type do differently?" (10min)

#### 8. The JSON Profile Client (35min)
This last hypermedia-style client is able to handle data profiles for display. With the new API, students will update their client to support the Profiles for Object Display (POD) pattern.

 * Describing Display Profiles (10)
 * Exercise: Including POD Support (15min)
 * Group Discussion: "Can we improve POD?"

#### 9. The JSON Profile Client and Change (40min)
With the updated clients that supports Objects-Addresses-Actions (OAA), we'll see what happens when the server adds an entirely new object and workflow to the API. Can the client handle this w/o any changes?

 * Adding the Notes Object Workflow (10min)
 * Exercise: Including Notes Support (20min)
 * Group Discussion: "Why use the Collection+JSON Media Type?" (10min)


#### 10. Summary (25min)
A Short summary of the class lessons on H-Factors and the OAA Challenge.

 * The OAA Challenge (5min)
 * H-Factors for APIs (5min)
 * Client Capabilities (10min)
   * Plain
   * Link
   * Template
   * Profile
 * Quick Quiz: "Pin the Client on the Media Type" (5min)

