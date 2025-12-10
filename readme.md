In-Process Inspection for Production (SAP QM)

A complete, beginner-friendly, functional SAP QM project demonstrating how In-Process Inspection is executed during production using inspection type 03.
This project is designed for SAP QM consultants to showcase real-time functional execution without any coding.

1. Project Overview

        In-Process Inspection is a key Quality Management activity performed during the production process to ensure that the semifinished product meets the defined quality standards before final processing. 
        This project covers the complete SAP QM cycle including:
              
              Routing setup with Inspection Characteristics
              Production Order Creation
              Inspection Lot Generation (03 - In-Process)
              Results Recording
              Usage Decision


2. Objectives

        This project demonstrates:
        
              ✔ How an in-process inspection is triggered during production
              ✔ How to configure and assign inspection characteristics
              ✔ End-to-end QM cycle for inspection type 03
              ✔ How results are recorded and decisions made

3. SAP Transactions Used
          
            Purpose	                       T-Code
            Create Material	             MM01 / MM02
            Create Routing	             CA01
            Assign MICs	                     QS21
            Create Production Order	     CO01
            Results Recording                QE51N
            Usage Decision	              QA11
            Display Inspection Lot	      QA03

   
          
4. Process Flow 

            i.     Create material with Inspection Type 03
            ii.    Maintain in-process MICs (Master Inspection Characteristics)
            iii.   Create Routing and assign MICs
            iv.    Create Production Order
            v.     Order release triggers an In-Process Inspection Lot
            vi.    Record results
            vii.   Perform Usage Decision
            viii.  Review inspection documentation



👤 Author

Satyanarayana Siddineni
SAP Functional Consultant
