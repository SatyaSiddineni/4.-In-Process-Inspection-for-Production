In-Process Inspection for Production (SAP QM)

This project demonstrates the complete execution of In-Process Inspection (Inspection Type 03) in SAP Quality Management (QM). It covers the setup, process flow, test data, screenshots, and deliverables required for showcasing a practical SAP QM scenario for your portfolio.

1. Project Overview

       In-Process Inspection is a quality control activity performed during production to ensure that semi-finished or in-process materials meet predefined quality standards before moving to the next stage of manufacturing.

                This project walks through the end-to-end steps, including inspection lot creation, results recording, usage decision, and SAP transactions involved — without any coding (functional only).


2. Business Scenario

        A manufacturing company produces a semi-finished material. During production, the company performs an in-process quality inspection to ensure intermediate quality standards are met before final assembly.
        SAP QM triggers Inspection Lot Type 03 when the production operation is confirmed

4. SAP Transactions Used
          
            Purpose                     T-Code
            Create Material              MM01 / MM02
            Create Routing              CA01
            Assign MICs                     QS21
            Create Production Order       CO01
            Results Recording              QE51N
            Usage Decision              QA11
            Display Inspection Lot       QA03

   
          
5. Process Flow 

            i.     Create material with Inspection Type 03
            ii.    Maintain in-process MICs (Master Inspection Characteristics)
            iii.   Create Routing and assign MICs
            iv.    Create Production Order
            v.     Order release triggers an In-Process Inspection Lot
            vi.    Record results
            vii.   Perform Usage Decision
            viii.  Review inspection documentation

6. Project Structure

       In-Process-Inspection-for-Production/
       │── README.md
       │── Dataset/
       │     └── In-Process-Inspection-Dataset.xlsx
       │
       │── Flowchart/
       │     └── Flowchart.pdf
       │
       └── Documentation/
             └── In-Process Inspection for Production process documentation.pdf



👤 Author

Satyanarayana Siddineni
SAP Functional Consultant
