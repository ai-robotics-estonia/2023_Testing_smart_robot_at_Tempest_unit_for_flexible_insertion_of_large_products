# TESTING A ROBOT IN TEMPEST LTD PRODUCTION UNIT FOR FLEXIBLE INSERTION OF LARGE-SIZED PRODUCTS INTO THE SPECIAL MACHINE

## Summary
| Company Name | [TEMPEST AS](https://tempest.ee/) |
| :--- | :--- |
| Development Team Lead Name | Tõnu Lelumees |
| Development Team Lead E-mail | tonu.lelumees@imecc.ee |
| Duration of the Demonstration Project | 11/2023-07/2024 |
| Final Report | [Example_report.pdf](https://github.com/ai-robotics-estonia/_project_template_/files/13800685/IC-One-Page-Project-Status-Report-10673_PDF.pdf) |

# Description
## Objectives of the Demonstration Project
The goal of the demo project was to implement and validate a robotic workplace for placing abrasive belts on a production line, and to test and validate the robotization and automation solutions to automate monotonous manual work in the company to increase flexibility, productivity and production volumes.

## Activities and Results of the Demonstration Project
### Challenge
The current situation in the workplace is to execute physically exhausting and routine operations by machine operator when inserting abrasive belts into the machine. If the production machine has a capacity of 1200 passes per day, this means that the person has to raise his hand above his head 1200 times, including the product. Some products can weigh 5-7 kg, while being 2-4 meters long and at the same time soft, so making this movement is a difficult and repetitive activity. As a result, people complain of shoulder, back and knee problems. The challenge of the project was to test and analyse the possibility of using a robot to effectively place abrasive sheets with different properties into the corresponding slots of a machine tool. Considering the fact that the source material is large-sized sheets of different materials and with different degrees of stiffness, attention had to be paid to the creation and validation of a special EOAT and the determination of dependencies between the material used and the EOAT. At the same time, the possibilities of using AI to solve situations more easily and to make rational decisions had to be analysed.

### Data Sources
- Description of the robotized workplace,
- Nature of the production process,
- Product nomenclature,
- Parametric description of products,
- Production quantities,
- Working conditions,
- Internal production communication networks (electricity, compressed air),
- Production layout .

### AI Technologies
- AI-based OEE analysis and optimization model,
- AI-supported decision-making system,
- Self-learning mechanisms,
- Data-driven automation control .

### Technological Results
Results achieved: 
1. The collaborative robot UR 20 was selected for servicing the device
2. The required lifting force, number and dimensions of suction cups, type and parameters of the vacuum generator were calculated and the results were applied to the design of the EOAT (vacuum gripper)
3. The necessary EOAT (pneumatic gripper) was adjusted and validated, and the corresponding prototype was manufactured
4. The robotized workplace for servicing the device was adjusted and validated
5. The robot's work cycle was implemented and validated
6. Device servicing tests were carried out in the robotized test workplace using different product materials
7. The results of repeated tests were analysed and observations for further activities were made (the results with fabric-based materials turned out to be very positive)
8. A universal model for the creation and validation of pneumatic grippers was presented
9. A model for the effective implementation of work in a robotized workplace and an AI-based OEE analysis and improvement model were presented
10. A risk analysis and recommendations for further activities in the company were prepared, along with the approximate cost calculation of the industrial variant

### Technical Architecture
- Robotized test workplace,
- Test with textile-based materials, 
- Test with paper-based materials,
- Model for designing vacuum grippers and result,

### User Interface 
In this solution, the collaborative robot UR 20 user interface was used to control the robot's work cycle for assembly operations.

### Future Potential of the Technical Solution
The solution has potential for broader use in other manual workstations involving repetitive material handling. With adaptations, it could support various gluing or assembly processes. Integration with a smart feeder system may enable partial or full automation in similar industrial settings. The concept promotes safer, more ergonomic workplaces and can increase productivity in small-batch or custom production environments.

### Lessons Learned
Thin sheet-shaped products made of various materials are widely used in production and industry. The traditions of robotization in this field are very small, unlike, for example, placing bottles in boxes with robots, moving various packages with robots, etc. This project provided information on which to base solving tasks of moving and installing large-sized soft material products. The principles of designing various special pneumatic grippers for moving and installing sheet-shaped soft products with robots were analysed, what are the key parameters for this type of tasks, how to control them and what benefits could be obtained from using AI. Testing showed that grabbing the abrasive sheet material with the collaborative robot's gripper and placing it into the narrow slots of the gluing machine is possible and successful in case of stiffer, thicker materials but difficult in case of thinner sheets because the edge of the sheet material rolled up. Additionally, the wider is the sheet material, the more difficult the task is. To accomplish the automation task in full extent and to overcome the probleem of the edge rolling, it is necessary to design and build a special sheet material guiding fixture. Since the widths and material characteristics vary greatly, building a flexible guiding fixture with automated control and AI support is unreasonably complex and expensive for the current production.

