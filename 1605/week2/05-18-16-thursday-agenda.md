# Thursday 5-18-2016 Pahlka Posse Meeting Agenda

### Kickoff @ 12:00

 * 12:05-12:20:  Goals for the posse this module - personal and collective
    *  1 technical skill you'd like the opportunity to work on
    *  1 soft skill you'd like the opportunity to work on and/or 1 experience you'd like to have
    *  1 collective goal you'd like to be a part of
 * 12:20-12:25:  Planning for our work sessions/attendance
 * 12:25-12:40:  Explore the code base - Get familiar with the project
 * 12:40-12:50:  Goals for Fri - what can we expect to accomplish?
   * An app for people to be able to find a neighborhood that best suits them
   * Shows a map where they input three destinations and it calculates the best neighborhoods based on transit time
   * They can input cost and it calculates neighborhoods based on that
   
* 12:50-01:00    Choose groups for work time
 * mapping work  
  `replace with name ex: July`  
  `replace with name ex: Patrick`
  `replace with name ex: Karina`
 * rails work google api(this might be finished)  
  `replace with name ex: nonaps`  
  `replace with name ex: Sonia`  
 * rails work creating methods for calculations using presenters, or a model  
  `replace with name ex: Thom`  
  `replace with name ex: Kerry` 
pending: Marina and Deb and maybe Andrew

## MEETING NOTES:
* Everyone should feel free to openly articulate why they are here. 
   * July- excited to be a member! Technical skill: learning how to render the documents in response to the API. Soft Skill: foster the same happy and passionate environment from last module. Getting new peeps. 
   * Patrick- Technical skill: Excited to get into the location stuff! Soft Skill: Looking forward to getting dealing with real world problems. 
   * Sonia- Technical skill: Wants to understand more about the implementation of the project(web-interactions). Soft skills: Would enjoy becoming capable of using github in a way that is beneficial to the community. 
   * Andrew- Technical skill: is lookig forward to helping everyone out in general(prefers javascript). Soft skill: would like to practice becoming one who takes directions well. 
   * Thom- Technical skill: would like to practice the skills that he doesn't necessarily get graded on. Soft skill: Leadership skills-- would like to get them on point an expand to different roles in the process. 
   * Kerry- Technical skills:  would like to know more about APIS in general(how to evaluate one and bring it into project). Soft skill: would like to feel comfortable telling people what to do when they decide to be here out of their own accord. 
   * Karina- Technical skill: Javascript and APIs in general(go hand in hand apparently). Soft skill: Time management. 
*ATTENDANCE- 
   * Don't feel bad for not coming but keep everyone in the loop. 
*ABOUT THE APP: 
   * we only have one views page
   * controllers- there's only one.. there's a routes page that sends you to the controllers and from there we render the appropriate view. Addresses aren't being passed in as a param in the home controller yet(we need that functionality)
   * Maps- going over hw to render maps in javascript to work more efficieently with mapbox
   * "featuredLayer" is part of mapbox-- it allows for you to add new layers to your map. Right now, we only have the usCoordinates layer. We want to add the coordinates for the metro area bus routes, neighborhood borders and metro area in general. 
   * We might want to look into geo coder to get more accurate centers to our neighborhoods. 

