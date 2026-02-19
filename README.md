# REST API Design & Documentation

This repository demonstrates approaches to designing, documenting, and preparing REST APIs for development.  
It includes examples of:

- **API Modeling** – defining operations, boundaries, and interaction flows  
- **OpenAPI Specification** – documenting endpoints with success & error handling  
- **Development Tickets** – translating product requirements into backend tasks  

---

### 🧩 Main Artifacts

- 👉 [API Modeling](https://github.com/edmnikolaeva/pet_store/blob/main/%D0%BC%D0%BE%D0%B4%D0%B5%D0%BB%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5_API_lucky.pdf)  
- 👉 [OpenAPI Specification](https://github.com/edmnikolaeva/rest/blob/main/open_api_registration_book_store.yaml)  
- 👉 [Development Ticket](https://github.com/edmnikolaeva/rest/blob/main/%D1%82%D0%B8%D0%BA%D0%B5%D1%82_%D0%BD%D0%B0_%D1%80%D0%B0%D0%B7%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%BA%D1%83_rest.pdf)

---

<table>
<tr>
<td>

### 🐾 [API Modeling – Pet Insurance Feature for Pet Store Mobile App](https://github.com/edmnikolaeva/pet_store/blob/main/%D0%BC%D0%BE%D0%B4%D0%B5%D0%BB%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5_API_lucky.pdf) 

- **Domain:** [Pet Store Mobile App](https://github.com/edmnikolaeva/pet_store/)
- **Purpose:** Enable users to purchase pet insurance directly in the app as part of the shopping journey
- **Scope:** High-level API boundaries, operations, and interaction flows
- **Value**:
  - Increase average order value via value-added service
  - Improve user trust & loyalty through pet care offerings
  - Differentiate from basic pet shops by providing insurance convenienc
- **Related Artifacts**
  - [openAPI Specification](https://github.com/edmnikolaeva/pet_store/blob/main/api_lucky.yaml)
  - [C4 Model](https://github.com/edmnikolaeva/pet_store/blob/main/C4_lucky.jpg)

</td>
<td width="220">
<img src="https://github.com/edmnikolaeva/rest/blob/main/sample1.png" 
     alt="Visual Anchor — Main Screen Prototype" 
     width="200"/>
</td>
</tr>
</table>

---

<table>
<tr>
<td>

### 📚 [OpenAPI Specification – User Registration Endpoint for Online Bookstore](https://github.com/edmnikolaeva/rest/blob/main/open_api_registration_book_store.yaml)  

- **Domain:** Online bookstore
- **Purpose:** Provide a secure user registration flow to create new accounts directly from frontend
- **Scope**
  - Single REST endpoint: POST /register (or similar path)
  - Input: user profile data (name, email, password, etc.)
  - Output: success confirmation or field-level validation errors
- **Value**
  - Frictionless onboarding → higher conversion from visitor to registered user
  - Immediate feedback on input errors → better UX and fewer support tickets
  - Standardized, documented API → faster frontend-backend alignment & fewer integration bugs
- **Related Artifacts**
  - [UML Activity Diagram](https://github.com/edmnikolaeva/uml_diagrams/blob/main/uml_activity.jpg)

</td>
<td width="220">
<img src="https://github.com/edmnikolaeva/rest/blob/main/sample3.png" 
     alt="Visual Anchor — Main Screen Prototype" 
     width="200"/>
</td>
</tr>
</table>

---

<table>
<tr>
<td>

### 🎥 [Development Ticket – Content Sorting by Critic & User Ratings](https://github.com/edmnikolaeva/rest/blob/main/%D1%82%D0%B8%D0%BA%D0%B5%D1%82_%D0%BD%D0%B0_%D1%80%D0%B0%D0%B7%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%BA%D1%83_rest.pdf)
 
- **Domain:** streaming service
- **Purpose:** Improve content discovery by letting users sort the critic and community (users) ratings
- **Scope:** Add criticsRating field and sorting parameters to relevant API endpoints
- **Value:**
  - Reduce choice paralysis → lower bounce rate on catalog page
  - Highlight expert-validated content → build trust for new/niche titles
  - Complement existing user ratings → cater to different user preferences
- **Related Artifact**
  - [UML Sequence Diagram](https://github.com/edmnikolaeva/uml_diagrams/blob/main/uml_sequence.jpg)

</td>
<td width="220">
<img src="https://github.com/edmnikolaeva/rest/blob/main/sample2.png" 
     alt="Visual Anchor — Main Screen Prototype" 
     width="200"/>
</td>
</tr>
</table>


---

### Related Artifacts

- 👉 [JSON: HTTP Request & Response](https://github.com/edmnikolaeva/json)
- 👉 [XML & SOAP](https://github.com/edmnikolaeva/xml)
- 👉 [Architecture](https://github.com/edmnikolaeva/architecture) 
- 👉 [C4 Model](https://github.com/edmnikolaeva/C4)
