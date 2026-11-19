
# Project 1: EMS Station

## 1. Project Overview
For this project, I designed and programmed an Emergency Medical Services station simulation in Snap!. In the real world, ambulances and fire trucks need a fast, safe way to pull out into busy traffic during an emergency without risking a crash.

To solve this problem, my Snap! program keeps a traffic light flashing yellow so regular cars drive with caution. As soon as an emergency is triggered, the program changes the traffic light to stop traffic, dispatches the emergency vehicle on screen, waits for it to pass the exit checkpoint, and then resets the traffic light back to normal.

---

## 2. Planning

### Key Design Decisions
* **Stage and Sprite Layout:** I laid everything out like how it says on the curriculum page.
* **Traffic Light Logic:** I used the RGB code block to pick which lights it would go to
* **Emergency Trigger:** The code starts by clicking an arrow key or clicking the green flag

* **Design Scope:** I focused entirely on building and testing the logic, sprite animations, and traffic-control sequence inside Snap!

---

## 3. Development Process

### Stage 1: Setting Up the Stage and Sprites
* **What I worked on:** Creating and positioning the EMS station backdrop, traffic light costumes, and emergency vehicle sprite in Snap!.
* **Why it mattered:** Getting the visual layout and sprite starting positions right first gave me a clear setup before writing the control scripts.

### Stage 2: Programming the Traffic Light and Emergency Sequence
* **What I worked on:** Writing the loop that keeps the traffic light blinking yellow during normal operation and switching it to red when an emergency is triggered.
* **Why it mattered:** Coordinating the timing between the traffic light changing and the vehicle moving prevents everything from happening at once.

### Stage 3: Testing the Full Sequence
* **What I worked on:** Running the program multiple times to check that the vehicle resets cleanly and the traffic light goes back to blinking yellow after every run.
* **Why it mattered:** Testing the reset loop made sure the program could run over and over without getting stuck in emergency mode.

---

## 4. Code

### Normal Operation Loop
* **What this code does:** In snap, you stop the yellow light from blinking during an emergency by interrupting or pausing the blinking loop using a variable or a script stop block.

### Emergency Sequence and Traffic Light Control
* **What this code does:** • When an emergency is triggered, the script sets the emergency state so the blinking yellow loop pauses, switches the traffic light costume to solid red to stop traffic, plays the siren sound effect, and broadcasts a message to tell the emergency vehicle sprite to drive out onto the road.


### Vehicle Exit and System Reset
* **What this code does:** : Once the emergency vehicle sprite finishes moving across the stage and reaches its exit position, the script hides or moves the vehicle back to its starting spot inside the station, resets the emergency variable back to normal, and broadcasts a message so the traffic light begins blinking yellow again.

---

## 5. Snap! Project Link
* **snap program** https://snap.berkeley.edu/snap/snap.html#present:Username=lvhs4&ProjectName=EMS%20Project%20-%20New%20Starter%20Code%204%2024

---

## 6. How the System Works


### Processing
1. **Normal State Check:** The code runs a loop that flashes the yellow traffic light while waiting for the emergency trigger.
2. **Stopping Traffic:** Once triggered, the program stops the blinking yellow light and switches the traffic light to solid red.
3. **Dispatching the Vehicle:** Next, the code moves the emergency vehicle sprite out of the station across the stage.
4. **Resetting the System:** Once the vehicle reaches the end of its path, the program resets the vehicle position and switches the traffic light back to blinking yellow.


---

## 7. Testing and Debugging

### Challenge 1: [Name of First Coding Bug]
* **What happened:** A lot of things went wrong with this project since, this is my first coding AP project it was very confusing .
* **What I thought caused it:** I think I didn't pay enough attention
* **What I changed:** I started paying better attention
* **Result:**I go the work done
* **What I learned:** Patience and complete attention will always help.


---

## 8. Final Product
When the Snap! program runs, it follows this full sequence:
1. **Normal State:** The traffic light flashes yellow continuously while the station waits for an emergency.
2. **Emergency Trigger:** When the emergency starts, the yellow light stops flashing and switches to solid red.
3. **Dispatch:** The emergency vehicle moves out of the station across the screen.
4. **Reset:** Once the vehicle clears the exit, the system resets and the traffic light returns to flashing yellow.

---

## 9. Reflection

1. **What part of this project are you most proud of?**  
   This project page took really long

2. **What was the most difficult part?**  
   The project page was the most difficult park because I wanted it to look really good

4. **If you had more tim what would you improve?**  
  How much attention I gave this project

