Download Link: https://assignmentchef.com/product/solved-csit121-lab5-java-applications-using-gui-and-event-handling
<br>
Following completion of this task, students should be able to:

<ul>

 <li>Write Java applications using GUI and Event Handling.<strong> </strong></li>

</ul>

<strong>Question 1 </strong>

Write a Java application using GUI for a construction company to handle a customer’s order to build a new house based on their choices.

Your application should declare a class called House that keeps the information of the model of the house, number of bedrooms, size of garage, and number of bathroom. Include suitable constructor, mutator, and accessor methods. Include also a method to calculate the total price of building the house. The price of the house depends on the model chosen, number of bedroom, number of bathroom, and number of garage chosen. The price of each individual part is mentioned below. Your application should maintain an ArrayList&lt;House&gt; to keep several orders of building different models of this house.

Create a JFrame containing the following components:




<ul>

 <li>A JLabel to display the title of the frame</li>

 <li>JComboBox to let the user select one of four models (the Aspen, RM100,000; the Brittany, RM120,000; the Colonial, RM180,000; or the Dartmoor, RM250,000).</li>

 <li>A label to display an image of a house and should change according to the house selected from the JComboBox You need to provide your own image of the houses.</li>

 <li>A JTextField to let the user enter the number of bedrooms (each bedroom adds RM10,500)</li>

 <li>Four JRadioButtons to let the user select the size of garage (zero, one, two, or three cars; each car adds RM5,000)</li>

 <li>A JTextField to let the user enter the number of bathroom (each bathroom adds RM3,500).</li>

 <li>A non-editable JTextField to display the total price.</li>

 <li>A JButton to calculate the total price of constructing the house chosen. Add an event handling method to this button. The method should retrieve the information typed by the user, create a House object using this information and add it to the ArrayList&lt;House&gt;, calculate the total price and display it on the JTextField for total price.</li>

 <li>A JButton to display all Houses Add an event handling method to this button. When the user click on this button, display the details of all the House ordered (all House object in the ArrayList&lt;House&gt;) together with the price of each one. You may display the details in a dialog box.</li>

 <li>A JButton to quit from the application. When the user click on this button, the application should terminated. Add suitable event handling method for this.</li>

</ul>




Use suitable layout managers and event handling for your application. Be creative in positioning your GUI components on the frame and it must be attractive and easy to use. You are not allowed to use the NetBeans GUI builder for this task. All components need to be created and added to the frame using codes.











