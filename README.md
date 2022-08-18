# Medical-Care

## Motivation
* Traditional file systems are susceptible to a lot of problems including :
  * Data might be difficult to retrieve – just to find a record one might have to search through all the data
  * Data redundancy and inconsistency which may lead to a lot of future problems
  * Data security can also be an issue – physical registers can be hard to maintain and access
* These problems can be effectively eliminated by using a systematic Database system, and the Medical Industry being such a critical industry where the data plays a very important role, it made complete sense to make a fool-proof project that can take care of the whole process - start to end, while maintaining data consistency and integrity, additionally also be user friendly. 

## Functionalitites
* A full-fledged three tier system, with separate dashboards and privileges for each entity - Admin, Doctor, Patient has been implemented.
* All three groups also have separate register and sign up interfaces.
* A Doctor can apply to work in the hospital, or can also sign-up if he is already approved as a doctor.
* Admin holds the power to manage the doctors and their approvals, and appointments of each doctor - with a concurrency of thoughts from the doctor.
* The patient can also register with a preference of a doctor for his checkup, and this shall be approved by the admin only if it matches with the interest of all the stakeholder, i.e. the doctors, patients and the admin.
* If a patient is already registered with a certain condition and is being diagnosed by a doctor, he can still apply for another appointment with another doctor - because in the real world it may happen that at one point of time, a person can suffer from multiple problems.
* A doctor also has the power to reject an appointment based on his availability and can also communicate with the admin for the discharge of a patient, which is finally to be executed by the admin himself, after making sure that all formalities are clear.
* The admin before the discharge of a patient can also generate a discharge bill - which includes the various expenses that the patient owes the hospital.
* The Admin can also view all details of each patient and that patient’s records, and each doctor’s details. He also has the authority to update their details as and when needed.
* We have also included a Contact Us section, where the user of the app can send feedback to the developers/admins about their experience.

## ER Diagram

![ERDiagram](https://user-images.githubusercontent.com/80578052/184318551-2a638951-b41e-4871-aa0c-0d17cb642b00.jpeg)
