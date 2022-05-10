0x21e235ba42d6cc31

Chapter 1 Day 1 Quests
1. The Blockchain is a decentalized, public, storage that anyone and interact with and view.
2. Smart contracts add functionality to the Blockchain that users interact with once deployed
3. Transactions change data on the Blockchain in exchange for money or some other tangible assets. And scripts are used to view the data on the Blockchain. 


Chapter 1 Day 2 Quests
Pillars of Cadence
1. Safety and security, clarity, approachability, developer experience, and resource oriented programing
2. I beleive these pillars offer quick scalability, easy of use, and a sense of security with the adaptation of a new system between new and experienced devs as well as end users.


Chapter 2 Day 1 Quests

Deployed Contract 
pub contract JacobTucker {

  pub var is: String

  init() {
    
    self.is = "the best" 

  }

} 

<img width="741" alt="image" src="https://user-images.githubusercontent.com/104784561/167518143-3d05b67d-a3f4-4283-a279-0dd97def5069.png">

Script Check

import JacobTucker from 0x03

pub fun main(): String {
  return JacobTucker.is
}

<img width="745" alt="image" src="https://user-images.githubusercontent.com/104784561/167518040-95f84471-77b6-4104-a123-fa6ffe9e3ed6.png">


