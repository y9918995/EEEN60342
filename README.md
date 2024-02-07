Basic Concepts of PS Stability, automated transcript 018-11-1 ---  
LECTURER: 
Hello again.
I'll start with the first chapter which deals with Power System Dynamics, introduction to it.
So, power system dynamics compared to the studies that you've done in the previous modules, deals with the transition from one state to the other.
While classical power flow equation describe the steady state of a power system when nothing changes, dynamics deals with transition from one state to the other, and how we move from operating point one to operating point two.
If this move is successful, so if we manage to reach a next steady state point, we talk about the system being stable.
If we don't do that, the system is obviously unstable.
So, the process of transition within two operating points is what power system dynamics is all about.
Why are we talking about power system dynamics in the first place? Because steady state as such, doesn't actually exist.
In all power systems, the changes are continuous starting from load fluctuation, generation dispatch, generation outages, line disconnections, faults.
So, there is something that is always happening in the system.
The system is in a way a live organism which never stays at rest.
So, because of this constant movement, then when we talk about steady state, we are actually talking about quasi steady state because that steady state as such, doesn't exist in real life.
The problem is that dynamics doesn't deal with these very, very, very, very small changes.
We kind of approximate them and we say, OK, this is steady state.
And dynamics will be something which actually move the system from one operating point to the other.
The dynamics, the nature of system dynamics can be various.
There are different disturbances and phenomena that cause a system to move from one operating point to the other.
They are globally divided into four areas into: wave phenomena, electromagnetic phenomena, electromechanical phenomena, and thermodynamic.
Wave phenomena are very, very fast.
They last between a few microseconds to several milliseconds.
Electromagnetic phenomena on the other hand, are between milliseconds and a second.
And electromechanical are between one second and several seconds.
The slowest ones are thermodynamic phenomena which last from several seconds to hours.
The causes of these different phenomena, wave, electromagnetic, electromechanical or thermodynamic, are associated with different physical processes that happen in the power system.
The fastest ones, the wave phenomena, are usually associated with the transfer of energy between the rotating masses in the generators and the loads.
Those are the electromagnetic ones.
The slower are the ones which are associated with variation of voltage and frequency which are needed to maintain system operating conditions.
And then we have very slow, which corresponds to the way in which the generation is adjusted to meet slow daily demand variations.
Now these are the phenomena which cause the change in electrical power In addition to those, obviously we have phenomena which are associated with disturbances such as the one resulting from typically lightning strikes which are fast wave phenomena wave surges in high voltage transmission lines.
These are typically caused by lightning strikes or switching operation and they last from a microsecond to several milliseconds.
They typically do not propagate beyond transformer windings.
Slower phenomena associated with disturbances as a difference from the previous ones we talked about the change in power, are caused by the operation of protection system or the interaction between the electrical machines and the network.
They typically are stopped or they do not move further than generator armature and damper windings and partly the network.
So, when I say generator armature and damper windings, I'm basically referring to a generator stator or damper windings on the rotor.
So, these are the phenomena which last up to a second typically.
So, these two groups, disturbances which include typically wave and electromagnetic phenomena, and variations in power which include electromechanical and thermodynamic phenomena are together forming a group of disturbances, a group of phenomena, which results in power system dynamics.
Now disturbances further that we have which are causing changes in rotor movement.
Rotor is obviously the rotating part of the generator.
So, changes in rotor movement are associated by the fact, by the changes of mechanical power in a way which moves the rotor.
So, rotor field and damper windings and rotor inertia together are those who are associated with the movement of rotor or causes the movement of the rotor.
And these oscillations are typically lasting to several seconds.
The prime mover and automatic control generation is another type of phenomena which happens later after the initial dynamic change.
And these are lasting from several seconds to hours.
Stability which is now the issue we're talking about after the disturbance.
So, whatever disturbance you may have, whether it's caused by wave phenomena, electromagnetic phenomena, electromechanical phenomena, or thermodynamic phenomena, we have issue of system moving from one operating point to the other.
If it manages to successfully attain the next operating point, the next steady state operating point, we're talking about a stable system.
If it doesn't, the system is obviously unstable.
So, any stability, including stability of power systems, is in fact a condition of equilibrium between two opposing forces.
Now if we consider a stable system, very stable system, we can see that the system state can be represented with this marble in a valley of potential energy.
So, the system is very firm, doesn't move anywhere.
If we cause a perturbation, the system moves out of the equilibrium, and then eventually returns to equilibrium state if this potential valley is deep enough.
If the system evolves due to changing operating conditions, we can see that this potential valley goes up, potential energy increases and it becomes shallower and shallower and at some point the system may move to instability because the balance between potential energy and the system disturbance, if any disturbance happens, will result in system losing steady state, losing stability and moving away from the point where it was before.
 
PS Stability Problem, automated transcript 018-10-12 ---  
LECTURER:
Now, if we consider a system which was in this state.
Where the potential energy is not so confined within a very deep valley.
And if the disturbance happens, a large disturbance.
Large enough to kick system over this peak, if you like, on the right hand side of your slide.
We can see that this disturbance can move this system into unstable operating condition.
And the system will never return either to the previous operating state or to a new stable state.
Now, definition as such of power stability is that is the property of power system that enables it to remain in a state of operating equilibrium under normal operating conditions and to regain an acceptable state of equilibrium after being subjected to a disturbance.
Whether small or large.
Now, the problem is therefore to maintain a balance between mechanical and electrical power.
If there is imbalance between these two, the system will obviously not be able to remain is stability.
Now, this description of the stability is typically done using mathematics obviously.
Differential equations and algebraic equations are used to describe the system model.
Differential equations describe mechanical motion of the generating units.
While algebraic equations are used for describing the behaviour of the network.
Now, obviously we need a coupling between these types of equations.
When I say differential equations are used for describing the mechanical motion of the generating units.
I am referring predominantly to electromechanical type of phenomena.
That we talked initially, which involves variation in the time frame between a second and several seconds.
Because when we talked about power system stability.
Most of the time we are actually referring to electromechanical stability or rotor angle stability.
Voltage stability we are going to talk about later.
Is another type of stability.
Which is typically considered under the umbrella of power system stability.
However, over the years, voltage stability evolved to independent area of research.
And many people would say look I work in power system stability or in voltage stability.
For people who say that they work in voltage stability it's clear where they are working in.
But people who say they work in power system stability is inherently assumed that they are actually working in the area of electromechanical or angular electromechanical phenomena, or angular stability.
Now, for any stability obviously we need some controls.
And these controls in most existing systems are predominantly associated with controlling generating units.
As you can see, the red bit on the left hand side of the slide.
Where we have a generator, automatic voltage regulator and power system stabilisers, governors and turbines.
So, these are all controls which basically control production unit.
In conventional power system, the main production unit is a synchronous machine.
The other parts of the system that have some control are obviously transmission controls.
Which are associated with reactive power and voltage control.
With high voltage transmission system.
And controls associated with high voltage DC with online tap changers.
Which is obviously transformer which can change turns ratio.
You've heard about that from other colleagues in other lectures.
Static voltage compensators.
Which are type of FACTS devices.
Generally, flexible alternating current transmission system devices.
So, SVCs, static voltage compensators.
TCSC's - thyristor controlled series compensation etc.
All belong to our larger group of FACTS devices.
These are devices placed in the transmission system to increase flexibility of the system.
In addition to that, we have the green block at the top.
Which is system generation control.
Which is frequency control and economic dispatch.
Which happens at certain times during the day.
Typically every half an hour.
And this is something that involves connection or disconnection of different generating units at different times to meet constantly varying load.
The requirement obviously of any power system control is to meet continually changing load demand for active and reactive power.
The system should supply energy at a minimum cost obviously.
And with minimum ecological impact.
And the quality of power supply must meet minimum standards with regard to constancy of frequency, constancy of voltage and level of reliability.
And this final part, constancy of frequency, constancy of voltage and level of reliability is the part of the second series of lectures within this module.
Which deal with quality of electricity supply.
So, basically we are covering within this module both bits.
The dynamic bit and quality of supply bit.
Now, the stability, as I said, is equilibrium between opposing forces.
In power system, the equilibrium happens between mechanical power coming from the turbine.
Which are these green trapezoid's on the right hand side and the left hand side of the slide.
And electrical power, which is basically load or demand coming from the network.
As long as these two are balanced, the rotor will rotate at constant speed.
So, we will have a system in equilibrium, in stable operating point.
Because of changes that happen in the system.
We basically distinguish between two types of stability.
One is rotor angle stability and the other is voltage stability.
As I said, rotor angle stability is associated with the movement of rotors of generators.
Because there is a movement involved we are talking about electromechanical oscillations.
Because we have electrical oscillations of electrical power.
As a consequence of mechanical movements of the generator rotors.
Voltage stability is not associated with any movement.
Is purely ability of the system to maintain steady state acceptable voltages at all buses in the system under normal operating conditions and after being subjected to a disturbance.
Now, the main factors affecting voltage stability is inability of power system to meet the demand for reactive power.
Which is not the case for rotor angle stability.
Where we are basically talking about balance between mechanical power coming from the turbine and electrical demand coming from the loads in the system.
The motion, the motion of the rotor, which is the essence angle of stability, is basically very similar to Newton's Law of linear motion.
Except we are talking here about rotational motion.
So, going through these equations.
I am not going to describe in detail.
We are talking about a movement of the turbine.
The turbine is fixed or very rigidly attached to the rotor of the generator.
So, the movement of the turbine forces the rotor of the generator to move.
Now, how fast this rotor will move will depend on the opposing force, which is coming from the load.
And that electrical torque coming from the load result of the currents induced in the stator of the generator will balance the mechanical torque coming from the turbine.
So, as long as these two torques are equal.
If you look their rotation equation for rotation at the bottom of the slide.
If Tm and Te are equal, the difference is 0.
So, the derivative is 0.
Which means the speed is constant.
Second derivative of angle.
This is equivalent to second derivative of distance in rotational environment.
Which is basically derivative of speed.
So, derivative of speed which is acceleration is 0.
The system doesn't accelerate.
And it's in steady state.
As long as Tm and Te are not equal, either positive or negative, there's some acceleration or deceleration.
If Tm is larger than Te then system accelerates.
So, gains speed.
If Tm is smaller than Te, then the difference is negative so the system decelerates slows down.
After some obviously derivations, we end up with final single equation at the bottom of the slide, which is a function f electrical and mechanical torque Te and Tm and J which is the inertia of the machine.
So based on this equation, we can basically explain the whole system dynamics and I will be referring to it a lot over the course of next several presentations.
The other thing that is to be remembered here, is that when the rotor moves, it rotates inside the stator now one full revolution of the rotor in case while it carries only two magnetic poles that you have heard about before, we have one sign wave.
So one rotation of the rotor results of one sign wave of induced voltages in the stator winding.
If we have two pairs of poles, so two north and two south poles, then one revolution will result in basically two sign waves.
So there is a difference between electrical degrees and mechanical degrees.
For a single pair of poles machine, machine has to poles, one rotor revolution corresponds to one sign wave.
Which means electrical and mechanical angles are the same.
In case when we have multiple machines, multi pairs of poles, then a single revolution of rotor, may result in more than one period of voltages induced in the stator.
So there is a difference between mechanical and angular degrees.
So electrical degrees becomes p times mechanical degrees.
So p is a number of pairs of poles.
So when they introduce this change into the original equation on the left hand side which is not dealing with electrical speed but with mechanical, then we transfer everything to electrical speed then the spear pairs in the denominator on the left hand side, so we have moment of inertia divided by p, second derivative of the angle and then difference between two torques.
Now, this now converts mechanical moment of the rotor, into the space of electrical moment.
So we are talking about rotation of electromagnetic field rather than rotation of the rotor of the of the generator.
So after some manipulation and introduction of electrical power, instead of torque, we end up with a slightly different form of electromechanical equation at the bottom of the slide, which shows the electromechanical equation expressed in per unit, while J is again moment of inertia, omega m is mechanical speed, SB is base power or rated power basically of the generator for conversion to per unit, p is number of pair of poles and Pm and Pe are mechanical and electrical power in per unit.
Interestingly, because the base for speed is singular speed which is one, this equation can be written alternatively with p electrical power and mechanical power or electrical torque and mechanical torque.
So there is no difference because in per unit Pm and Tm and P and T would be the same because the are power, the speed is considered to be one.
So, after further derivation as shown on the slide, we come to the final form of the swing equation which is given in the bottom right hand corner, which is a function of constant H which is inertia constant Not the moment of inertia, it's now inertia constant, and we have rotational speed in per unit single speed and mechanical and electrical power on the right hand side.
So, the final form once again of the swing equation is given above and as we can see as long as there is a balance between mechanical power and electrical power, or mechanical torque and electrical torque, we have no acceleration.
Second derivative angle with respect to time is zero, so the machine does not accelerate.
In case when there is a difference between these two, there will be either acceleration of the oscillation and because the second of the differential equation, we will have actually rotor angle oscillations.
Now, when this oscillation happen, we have variation in electromagnetic torque.
Electromagnetic torque, is the torque...if you go back to the previous slide, and look into this equation, the swing equation again, so as long as Pe and Pm are equal, there is no acceleration so machine is steady state.
If there is ant disturbance in the system, Pe will change because Pm electrical power is governed by the turbine so electrical power will not change, if we do not do something with the working fluid or the turbine.
Electrical power will change because of the changes of the system.
As long as there is slight (INAUDIBLE) in electrical power, Pm and P will become different and machine will accelerate or decelerate.
Now the changes in electromagnetic torque or electric power, can be expressed as a function of two components.
One which is in phase with the change in angle, and the other which is in phase with a change in speed.
The component which is in phase with a change in angle is called synchronising torque or synchronising power and component which is in phase with speed is called damping torque or damping power.
Corresponding coefficients obviously are called synchronising torque coefficient and damping torque coefficient.
Now these two components depending on their value, we may have different variation in electromagnetic torque and consequently because electromagnetic torque is coupled with mechanical torque in the swing equation, we will have overall variation in rotor speed.
Now let's look these oscillations, so these two components electrical and mechanical torque, sorry synchronising or damping torque coefficient or synchronising or damping power coefficient.
They can be related to something that is much more easy to comprehend than movement or rotation movement of the rotor in the synchronising machine.
So if we imagine a mass which is hang on the spring, spring has certain stiffness K for example so if we extend, if you pull the mass down and extend the spring and let the mass go, the mass will start to oscillate.
Obviously, as long as this spring strong enough to pull the mass back, the mass will oscillate.
If we pull the mass too forcefully downwards, we may extend and deform the spring and you will never be able to pull it back but you will assume at this moment that we are not doing that, so we're just pulling a little bit mass down, let it go and will start to oscillate around the previous balance steady state condition.
The stronger, the stiffer the spring is, the faster these oscillations will be.
And eventually because of the losses in the spring, the air resistance, this mass will stop to oscillate.
So as you can see on the right hand side, we have oscillations of the mass around the initial operating point they will last as long as the energy is not dissipated through losses due to the spring resistance and due to air resistance.
Now, this stiffness of the spring, this K is actually equivalent to synchronising torque.
More the stronger the synchronising torque is the more oscillations will result from rotor displacements from original position and the rotor will oscillate at a higher frequency as long as these synchronising force, let's call it force, is present and positive, rotor will be pulled back towards the original operating condition.
Same as I was talking about the spring, as long as we do not deform the spring, it will pull the mass back.
If the spring is very weak this pull will be slow.
If the spring is very strong, we'll have a lot of oscillations before the mass stabilises.
So stiffness of the spring is in a way equivalent to synchronising torque.
If you now take the same system and immerse the mass into a vessel full of say, very viscous motor oil.
And we repeat the experiment so we extend this spring and let the mass go.
The mass will oscillate again depending how stiff the spring is but now, in addition to losses in spring and in addition to air resistance, which are now much higher resistance.
There is a friction actually because the mass is moving into very viscous environment, it's not air anymore and this oscillations will be damped.
So the mass will return much slower towards the previous operating conditions and the results of oscillations will be much, much attenuating.
Much more attenuating than before.
So this resistance, whiskers, friction basically, that exist in the vessel with the oil in this experiment is equivalent to damping that we have in case of rotation of the rotor of synchronous generators.
Now this damping is coming predominantly form the damper windings which exist on the rotor of the generators.
We will review that later on in the next set of lectures but for now I assume that you have heard this before.
So the rotor damper windings whose role is basically to attenuate oscillations of the generator.
So these are the major source of damping.
In addition to damping coming from damper windings obviously we have a portion of it coming from field winding on the rotor and a portion coming from air resistance and friction in the bearings that the rotor is placed at.
However these air resistance friction bearings are very, very small and if there wasn't for damper windings actually and the field winding to some extent, we would have virtually zero resistance.
So to conclude, when looking back at the...
I'll go back few slides now again.
When I had this delta (T) equals Ts times delta, delta plus TD times delta, omega, this one.
So when we look at this rotor angle stability slide which describes the variation like might torque.
And when we look at synchronising torque and damping torque and connecting that the discussion about the experiment with the spring and the mass hanging first in the air and then in the vessel full of viscous liquid, synchronising torque and damping torque to a large extent determine how the rotor will behave once there is imbalance between mechanical and electrical torque.
Depending whether these synchronising lab torque are positive or negative, large or small, the nature of oscillation, the nature of system response, they will be very different.
And now going back to types of rotor angle instability, we may have two types; One is if the synchronising torque component is not strong enough.
So if the stiffness of that spring remember is not strong enough, the rotor will never be able to return to previous operating position or the mass once the spring is extended will never come back.
The spring will either break or the mass will remain hanging in the air without springs ability to pull it back.
So if synchronising component is not strong enough, the rotor once starting to accelerate, will never be able to return to previous operating position.
It will practically run away.
Of course the rotor doesn't run away anyway but once the speed is about 10 or 15% of the rate the speed protection of will disconnect the generator because the synchronising torque was not strong enough to pull the rotor back to its previous operating position.
On the other hand, if the synchronising torque is strong enough, it may pull the rotor back after initial swing in one direction but if there is no damping, these oscillations will theoretically continue to last forever.
Obviously there is no such a thing as oscillations lasting forever because there will be always some loss in the system.
But if the damping is very, very, very low, oscillations will last for very, very long time.
And we cannot tolerate that because typically, in a typical system you want these oscillations to disappear within five to seven seconds.
Exceptionally in very large systems, we can tolerate them to be say ten or fifteen seconds.
With more than that, it requires immediate action and additional control efforts to make sure that those oscillations do not persist for a very, very long time.
So the lack of damping torque will result in either, long lasting oscillations or in some cases, this damping torque can actually be negative.
So instead of reducing the magnitude from one side of the other, the magnitude of oscillations will continue to grow.
Now the oscillations will be present as long as synchronising is strong enough.
So if we look at the next slide, the slide which describes, typical forms of rotor angle instability.
You can see various combinations of possible rotor angle responses depending on the relationship and the sign and the magnitude of synchronising and damping torque.
So if we look at the bottom right hand side slight, which is the one which represents three most typical responses observed in real systems.
We can see the response one, case one, solid line.
Looking at that response we can see that after the initial disturbance the rotor starts to accelerate and then the oscillations appear and after a certain period of time oscillations become smaller and smaller and eventually if we continue this after three seconds as shown on this line, the oscillations would disappear.
This is the case, it is a typical stable case when both synchronising and damping torque locations are positive.
Case two, is the example of insufficient or negative synchronising torque.
So after the initial acceleration, if you can see once the rotor reaches certain value, instead of going down as in the previous case of the solid line case one, the rotor actually continues to accelerate and angle increases.
So synchronising torque was not strong enough to pull the rotor back to its previous operating condition.
Case three, is the case with synchronising torque is sufficiently strong so the rotor accelerated, the synchronising torque was large enough, it pulled the rotor back to its previous operating condition which resulted into rotor coming down reducing the angle and then oscillation started to appear.
So we have one, two cycles however, because damping torque is insufficient or negative, in this case negative, the oscillation, the monthly oscillations grows and at some point again they lose synchronism.
So these three cases are examples of typical responses observed in real life and they once again to make sure that you remember them well.
The first once is a stable oscillatory response with positive damping and positive synchronising torque.
Case two is a periodic instability resulting from...
Negative or insufficient synchronising torque.
And the case 3 is oscillatory instability.
Resulting from positive synchronising torque and insufficient or negative dumping torque.
Now, these were the ways how the oscillations may appear.
How they may look depending on the relationship between synchronising and dumping torque.
Which exists inside the machine.
The other thing that we have to look at here is why these oscillations appear at the first place.
It can be because of that, because of the nature how the disturbance or the size of disturbance that is generated and it affects system here.
We divide rotor angle stability typically into small disturbance stability and transient stability.
Small disturbance often referred to as small signal stability.
Though I think that the small disturbance is much more physical irrelevant thing.
Because we are talking about disturbance that are causing variations not signals.
So, small disturbance stability is the ability of our system to maintain synchronism under small disturbance.
Now, the typical question here what is it, small disturbance? How do we define what is small, what is large? Now, small disturbance typically is considered to be disturbance which doesn't move operating point more than a few percent around its original location in the obviously multidimensional space of system parameters.
Now, when we do that in a single machine infinite bus system.
And if we want to track the systems small disturbance.
We typically disturb one of the parameters by a few percent.
Typically, no more than 5%.
That's when we are talking about one parameter.
For example, we may change the reference at point on automatic voltage regulator about 5% up or down.
And then, we observe the consequence of that change on rotor angle variation.
On the other hand, transient stability is a consequence for a larger disturbance in the system.
When we have either a loss of system components.
So, a loss of line, a loss of transformer.
Or more frequently.
Well, not so frequently but still more frequently in loss of line.
A fault in the system.
The fault either single underground fault, line to line fault, three phase fault etc.
Three phase fault is something that we are typically testing system stability against.
Even though these are the least frequent faults to happen in the system.
So, transient stability is the ability of a system to maintain synchronism when subjected to severe transient disturbance.
The other difference between the two, between small disturbance and transient stability, is that in case of small disturbance stability we always talk about system returning to previous operating point.
So, we disturb it a little bit around operating point.
And it comes back.
So, it starts to oscillate if it's stable obviously around the equilibrium.
And then, eventually returns to a point where it was before.
In case of transient stability, system may return to a point where it was before.
But it may also attain a stable operating point which is different from the previous operating point.
Because in case of transient stability, we have situations often when the fault happens.
And we disconnect the faulted component.
So, that the voltage of the system changes.
The power flows change.
the balance of power changes.
So, the system starts to oscillate.
Oscillates and then settles at a new operating point.
Which is still stable but different from the previous one.
So, these are too basic.
I would say differences between the two.
Apart from obviously being the size of disturbance.
But the difference in terms of new steady state, in case of small disturbance stability, the new steady state is the same as the older one, initial one.
In case of transient stability, the new steady state quite often is a state which is different from the previous one.
Now, that brings us to voltage stability.
Which, as I said in the beginning, many years when people start talking about system stability.
They talked...
When they would say OK someone is expert in power system stability.
People would typically consider them experts in both.
But over the years obviously the area developed.
And people working in voltage stability and people working in angle stability started to being involved in slightly different areas of work.
And then, over the years, obviously these two areas separated.
So, it's much more frequent today to say OK he is expert in voltage stability and somebody else is expert in power system stability.
While with this power system stability, voltage stability is typically not considered there as being part of it.
Because the nature of the phenomena that we are looking at is slightly different.
It is not always easy to distinguish between the two.
To be fair.
But principally the nature is different.
The nature of the problem is different because in voltage stability we are dealing with voltages alone.
So, there isn't much rotation involved.
There is not electromechanical equation as such.
As we are talking about when we talk about...
As we are dealing with it when we are talking about angle stability.
So, with voltage stability we are basically talking about the provision of reactive power, whether it's sufficient or not, to maintain system voltages.
And the whole idea here with voltage stability is after being disturbed, either due to small or large disturbance, whether the system will maintain its voltages within certain limits.
As you know, I hope you do.
Voltages, there is a very strong coupling between voltage.
Well, there is a stronger coupling between voltage, magnitude and reactive power.
And between real power and voltage angles.
Than it is between a voltage angle and reactive power, and voltage magnitude and real power.
So, when we are talking about maintaining voltage magnitudes within certain operating limits.
We are talking about provision of reactive power.
So, if there is enough reactive power in the system under normal operating conditions we will be able to maintain the voltage.
If there isn't sufficient provision of reactive power we would result, the system may result into may lead to low voltages.
And eventually, to voltage collapse.
Now, the main criteria, once again, is that at a given operating condition for every bus in the system, the bus voltage magnitude increases as the reactive power injection at the same bus is increased.
So, adding more reactive power pushes the voltages up.
Voltage stability is typically a local phenomenon.
So, it doesn't involve the whole system.
It involves parts of the system.
Several buses.
Few tens of buses if you want.
And if that is a very severe case, then we may lead, then we have the voltage collapse.
Which is the result of sequence of, if you like, unfortunate events.
Which are combining voltages stability.
And leading to a low-voltage profile in a significant part of the system.
And then, we have blackouts.
And then, we talk about blackouts in Sweden, blackouts in eastern United States, blackouts in western United States.
There was a very big blackout in London a few years ago.
Then we have blackouts in Australia, China, India and so on.
There is a whole list of these events that happened around the world.
Good thing though is they happen very rarely.
Another good thing, if there is a good thing in a bad thing, is that whenever they happen.
That spurs the research in voltage stability.
And new discoveries are made.
And new solutions are provided.
So, the frequency of these events tends to be lower and lower as we learn more about the phenomenon behind it means we are designing solutions, which can protect the system from such events.
As I am not going to talk at extend about voltage stability during this course.
I will review few of the issues related voltage stability now.
So, that you at least have.
An idea what load instability is all about.
Load instability is typically observed through nose curves, because they resemble some people noses, well, everybody's nose I suppose, or P-V curves which show how the voltage at the bus there is as the power increases.
So as you can see on the top left corner of this slide, as the power at the bus increases depending on the power factor, the voltage drops since the system typically operates with lagging power factor in inducting mode if you like, the voltage is towards the...at the bus are becoming lower and lower as the power demand at the bus increases.
In case when we have a leading power factor which means that capacitively the line is loaded capacitively or it has more capacitance in case of cables, light loading cables for example, then we may see that there is a certain point of voltage goes up and then eventually depending on the balance between active and reactive power, and the capacitive and inductive load across the line, we may have something called this frontier effect where the voltage at the end of the line is higher than at the beginning of the line but this is only in cases with the very capacitive lines which are loaded with such impedance loading or natural load of the line.
But this is something that you dealt with in other modules and I'm not going to talk about this, I'm going to talk about typical performance of a typical bus in a power system where the load is with a lagging power factor where current lags behind voltage basically and we have a reactive power demand not injection.
So, as we increase real power, the voltage at the bus typically drops.
And in the bottom side of the slide, in the bottom right hand side corner, you can see this dependence between voltage and reactive parts is slightly different scale, different perspective, but you can see these shapes are about the same.
So there is again something like a v curve in this case, or again nose curve if you rotate it, if you rotate the bottom right hand side figure in the same way as it was presented in case of real power.
If the voltage goes up you will see that the shape of the curve is about the same.
So there is a point in this curve which is shown by a locus of critical points on both of them, this dash line across the nose points on all curves.
So up to this point, if the voltage...
If you go now back to conventional P-V curves shown in top left side corner, so if you increase real power, the voltage will typically go down and the work will reduce up to the point where dash line intersects the side-line.
This is called critical point.
Because once the power continues to increase beyond that point there is no stable operating point anymore.
So if you lower the line which shows one power factor one, as you can see once you reach loading of about one on the horizontal axis, on the x axis, we see that there is intersection between this locus of critical point and nose curve, and that is the critical point.
Beyond that point if you continue to increase the power, we can not do anything because that curve doesn't exist practically anymore.
So further, move along the solid line shown as...
in this case we're talking the curve which refers to power factor one, the bottom part the curve below this locus or critical points is unstable region.
So, for a system to be voltage stable we have to stay above this critical nose curve.
OK, so, let's look now what are the causes of this instability.
The causes of voltages not being able to stay within a limit that you would like the to be.
As you know typically we want them to be between plus minus 5% at a higher voltage level and plus minus 10% typically at a lower voltage level.
So why...what is it that contributes to voltages being outside these limits? Basically, they're natural characteristics, the impedances of the lines, length of the line, topology of the network, generator characteristics, whether generators have enough capacity to support voltages because they need a source of reactive power in the system, are actually increase generator.
So, if we operate all synchronised generators with power effect one, meaning that every single megawatt ampere is converted if you like in to megawatt...
So, there is no megawatts available in the generator, so any voltage deviation from rated which would require injection of reactive power will not be able to be compensated because there is no reserve of reactive power.
That's why after all, synchronised generators are operating with power factors which are not one but typically lower.
Even though they would like to operate with power factor one because most of them are paid based on megawatts unless some additional payments are made for them to provide which they are actually, to provide reactive power, they would all like to operate with power factor one because this is how they make money.
But we ask them, system operators ask them to operate with lower power factor and compensate them from that so that in case of voltage variations additional power can be extracted from them and obviously within their capability limits so that the overall rating is not exceeded and then they can provide reactive power support.
So this is why generator characteristics are very, very important for that.
Obviously load characteristic is another very important component in voltage instability if not the...
well, I can't say the most important but certainly very important because depending on how loads behave following the voltage variation, we may require higher or bigger or lower support from other sources of reactive power.
And obviously there are other devices that can produce or consume reactive power which are capacitors, either regulated or non-regulated and whether they're shunt or series, they are there to basically one way or the other inject reactive power or enhance delivery of reactive power at given locations.
Now this is typical thing for systems which are designed using overhead transmission lines in case of systems with cables where the capacitance is much higher, in these cases, in this types of natural...
during the night for example when the load is very low they may have a situation where voltages are actually higher not lower than rated.
So, it's a problem of reactive power compensation in this case which is not injection of reactive power.
Rather, it's consumption of reactive power.
So instead of having shunt capacitors or series capacitors we use reactors which consume reactive power, so they will basically drop the voltages and bring them down to...
some that values...or values which are required that they be in within plus minus five or 10% of the rated.
So, to finish on this topic in general as I said voltage stability is not something that we're going to dwell any longer on about, but this is necessary...I think it's necessary background for you to be able to engage in conversation about voltage instability to a certain extent if you come across these issues.
So I will talk briefly about critical load demand and how the voltage stability is actually...
or instability can be visualised and explained using nose curves and load curves.
So, if you look on the left hand side, the Qs curve is our typical nose curve.
So curve which shows how voltage.
varies with real or reactive power in this case its reactive power but as we discussed few slides ago they have the same shape as both of them PV and QV curve.
So QS would be the capability of the system to supply certain amount of reactive power at a given voltage.
Curve QL is the actual load demand at that location.
So as long as these two curves intersect, we have a stable operating point from the point of view of voltage stability.
So if we look first to the left point intersection point u.
So if for some reason load if for some reason voltage at the bus increases, we would move along the QL curve first and what we can see at that point QS is larger than QL.
So the power supply by the system is larger than power demanded by the load and the voltage will continue to increase.
So we are not coming back to point you we continue to slide along QL curve to the right.
If for some reason starting again from point u, voltage drops.
Again looking at the QL curve, so reactive power at the bus reduces, we have a situation that voltage is lower and along QL curve QL is larger than QS.
So demand for reactive power at the bus is higher than or greater than provision that system can give.
So the voltage will continue to drop.
So again we are moving to the left now from point u, so system is not returning to equilibrium.
So that's why that point u is named u, which means unstable.
On the other hand, if they look on the right-hand side point s, in case of demand increase.
So we move from point s to the right along curve QL.
QL is a larger than QS, so demand for reactive power is larger than what system can supply, so the voltage will drop.
So we are coming back to point s, so moving back from the right to the left towards point s.
If demand at the bus reduces, so we move from point s to the left along curve QL then QL at this value reduced voltage is below QS.
So we have more reactive power at the bus than is needed, so the voltage is boosted and voltage moves to the right.
So we move then from the left back towards point s back to the right towards point s, so this point s is stable.
So looking at these two cards now s stable u unstable.
We can clearly see if the demand overall demand starts to increase then QL curve gets translated and moved upwards until the point where there is, I'm talking about the middle...middle graph on the slide, until there is a single point single value, it's not that anymore intersection point is basically tangent on QS curve.
So a single point which becomes a critical point.
So this is the last point where this system can operate because whatever system can provide along QS curve is the same as what demand is along QL curve.
So we have this critical point.
If the demand overall demand continues to increase these two curves becomes separated and we have a voltage collapse.
So looking back at the central diagram from the right to the left, if you are moving along curve QS from the bottom on the right hand side upwards to the left was point u, death part of the curve is stable.
Any intersection at that side between QL and QS will result in point s discussed in the first diagram on the left which is a stable operating point.
And we can do that the stable operating region would be to the right of the curve.
If we move further to the left, every intersection between QL and QS curves will result in unstable operating point, so we have unstable operating condition.
That's why this right-hand side of the curve is stable.
Now if you remember how the nose curve look like if you rotate this...this diagram such that voltage becomes vertical axis and reactive power horizontal axis then you will see that the top part of the nose curve is stable and the bottom part of it is unstable.
The final thing within this set of introductory discussion about system stability that I want to very briefly address is further subdivision of parse instability in terms of different times.
Before that though, there is very important thing that...
that should be mentioned here that all these stability subdivisions and broad if you like definitions that I was talking about, have been around for many years.
And in 2004 a paper report by the IEEE task force was published which classifies system stability and defined system stability many of these things that I was talking about, were based or derived based on that report.
In the meantime, so in last 15 years obviously the changes have happened in the system and we have many more devices in the system which are not necessarily conventional devices in a sense they operate as conventional synchronous machines and an apparatus that we had and still have in the system.
There are many more devices which are now power electronics based.
These devices starting from renewable generation connected through either partially through converters like double fed induction generators or fully through converters like full converter connected generators, wind generators or photovoltaics which are obviously completely connected through power electronics.
Either generation to one hand all load on the other hand the typical example that people will think of these days would be for example, at coequals because they are all connected when they're charging or discharging charging particular because then...
then would be loads if that is charging they can be looked at as the generators but if you talk about electrical load in the form of electrical equals, that's obviously connection through power electronics.
So not only like winkle but other devices you have in...in you know homes or in...in commercial industrial facilities are either variable speed drives or other devices connected through power electronics.
There are many more devices which are connected to power electronics.
Now behaviour of power electronics is different than behaviour of conventional synchronous generators.
So because of this proliferation of power electronics and power converters or inverters depends which side of the converter you are standing or and looking into the system, that changes the nature of system dynamics.
So dynamics I'm not going to discuss these changes here but these dynamics is different...
different from dynamics of conventional systems.
It enriches the overall spectrum of dynamic phenomena that we can see in the system because of that some of the phenomena that didn't exist before are now or have been observed now in the system it is likely they will be observed more and more.
So there are circumstances were converter transients convert interactions results in dynamics of different nature different...
Frequencies, different magnitudes etc.
So, that prompted discussions that probably we need to broaden the power system stability and definitions and power system dynamic definitions.
And there is a new taskforce created about a year ago.
Which is looking in enhancing or improving or not necessarily improving but adding including these new phenomena observed systems power electronics.
Including phenomena and dynamics observed in subsystems.
And trying to classify it within a scope of power system stability in general.
However, we are still discussing the conventional systems.
Where we have synchronised machines as dominated types of generation.
And when most of the loads are not necessarily connected through power electronic devices.
So, we are talking about in a way conventional systems.
In these systems, dynamics can then be divided based on the time frame too short term or transient stability.
Lasting typically up to 10 seconds.
Then, we have midterm.
Which is midterm stability or midterm dynamics.
From about 10 seconds to a few minutes.
So, we are talking here about some slower phenomena which are associated with large voltage and frequency excursions.
And then, we have long term effect, which last from a few minutes to tens of minutes.
Which are results of boiler dynamics in thermal units.
With some dynamic associated with operation hydro-turbines.
with automatic generation control and so on.
So, there are different time frames within which particular dynamic phenomena takes place.
This is very important for studies of power dynamics and power system stability.
Because depending on the time frame within which particular phenomena takes place, we need to use slightly different models.
We do not need to use same models for describing phenomena which lasts for example from a few minutes to tens of minutes.
As we would need to describe phenomena lasting between 0 and 10 seconds.
There is actually no need for that.
Because by the time the long term phenomena starts taking place.
So, from a few minutes onwards.
Shorter transient phenomena lasting from 0 to 10 seconds has finished.
Already gone.
So, we don't need to burden the system models with mathematical descriptions.
Which include the whole time frame from 0 to infinity when these phenomena do not overlap.
So, this subdivision is predominantly useful for selecting types of mathematical model.
Which will be appropriate for a particular type of study that we are going to carry on.
Now, there's further discussion about midterm and long term stability.
Obviously, there are some explanation on the next few slides.
Why they would happen and what the consequences of these would be.
And whether for example in case of long term stability when we have a system divided or splitting into different islands.
The question whether or not each island will reach a equilibrium state with minimum loss of load or not.
So, this is the question which is slightly different from normal power system stability considerations.
Because we are now talking about effectively more than one system, if we divide systems into islands.
So, typically when we talk about unstable system depending what the system is.
It's very important distinction to be made at the beginning.
So, for us for power system stability point of view the system is what we have at the time of observation.
If the disturbance, whether small or large leads to loss or disconnection of a single component of that system then our system lost stability.
The fact that this disturbance may result to disconnection of a single generator out of 100.
We still have 99.
And you may say, look, but we still have 99 generators that are still working.
Why are we talking about unstable system? Well, the system that we started with is the same as the one that we have after losing a generator.
Because loss of that generator may lead to disconnection of some loads.
It may or may not depending how fast we can redistribute those.
But typically, it would result in disconnecting some load as well.
So, that is the system that we had in the beginning, disturbed and different from the system that we have after disconnecting that unit.
So, system becomes unstable if a single generator is lost.
That's why when we talk about splitting a system into different islands and then looking into stability of individual.
And that's why we are talking about long term stability.
Because this is something which will typically happen after initial disturbance.
And after we have to separate systems in different islands.
And then, look what's going on with each of the islands after the disturbance.
And this is concluding slide in this section.
About the system stability.
You can see this subdivision of power system stability that I was referring to when I talked about a report that was written about division of power system stability.
Some 15 years ago.
Which was published in 2004 by they work on that stuff in 2001.
So, even though obviously it has been updated during the three years the taskforce was working on it.
Most of it was dealing with the power system stability of conventional system.
And that power system stability in those times, at the time of writing this report, was subdivided as you can see on this slide.
This is absolutely valid.
There is absolutely nothing wrong with it.
And this is what you are going to refer to during the course of this lectures.
But as I said, this is something which we have at the moment.
Or we had until very recently.
And now, predominantly due to proliferation of power electronics either on the side of the generation or on the demand in the system.
Some other dynamic phenomena have been observed.
And led to undesirable effects in some systems around the world.
And because of that, a group of people is looking into adding probably more boxes to this diagram.
And trying to capture and describe these new phenomena that have been observed in the systems.
So, I can give an advanced notice then in about two years you may look at a table like this discussing power system stability of subdivision, power system of stability.
Which will have more boxes than at present.
This is the end of the first chapter.
Which dealt predominantly with definition of power system stability.
And general classification of power system dynamics and why do we need to do that.
And we will stop here.
The next section, the next chapter, will deal with some issues related to modelling of generation, load, transmission components of the system.
Which is necessary for use to be able to build overall mathematical model.
That will be used for assessment of power system stability either small or large.
So, until next talking to each other, I wish you a good day.
 
Synchronous Machine Fundamentals, automated transcript 018-10-12 ---  
LECTURER: 
Hello again.
We are about to continue talking about power system dynamics and stability.
This time this next set of slides...
talks will be about modelling power system components from synchronous machines to loads and transmission components.
So we'll start with synchronous machines and then continue with the generator controls, extension system, power system, turbine regulators moving on to transmission lines, transformers and finally finish up with loads.
Some of this will be will be in more details, some less depending on the background that I believe you have had in the past.
But anyway for this section as for the previous one there are additional reading sources provided that you can read on your own and clarify the issues that I may have not covered deeply enough.
I obviously can not go into discussing everything in a component in a too lengthy detail because there is a lot of things that you have done in your previous studies, either as undergraduate, or as a part of this master class.
So we'll start with synchronous machine fundamentals.
So generator as such is obviously critical component for powers and dynamics because dynamics we are talking about is electromechanical dynamics, electromechanical motions in the system, electromechanical oscillations in the system which are as I said consequence of rotor changing its speed and because of that we have power fluctuations in transmission lines.
So generator is a part of the network and you can think of it as a beginning of the network.
It has some controls around it either automatic voltage regulator exciter, we have a governor, turbine.
So this generating unit as one.
Then is connected to a step up transformer which rises the voltage to a transmission level then it's connected to the rest of the system.
Now one very very important thing to bear in mind whenever we talk about power system dynamics is that we are dealing how with the real life equipment.
With devices which are very very very large.
so if you look this photographs you can see how big these machines are.
In our discussions we'll at the end, end up describing generator by a single swing equation.
Delta omega delta T equals one over 2HPM-PE.
That would be synchronous generated for us for most of the discussions in this module.
However that one, first all the differential equation actually represents device like the one shown in this figures.
And if you look at for example the central figure which shows the stator and rotor of hydrogen generator, the people which stand around it is much much much much smaller than this huge drum, which is the rotor of hydrogen that has been inserted into the stator.
So again when we...when you as practicing engineers look at the results of some studies that you are going to do using commercial software packages because no one today develops their models.
So the models for the power systems components are developed many years ago.
They are good enough, very good actually.
They have been built in many commercial software packages and is such widely used for real life systems studies.
So very very few people apart from research students are developing their own models nowadays.
And our purpose here will not about developing model research.
I will try to explain some detail about the models how they are built and why they are built as such.
But we are not going to go deeply into modelling.
We will rather try to explain why some models or some forms of the models is needed and what are the results that you've obtained from this commercial packages and how do we interpret them.
So my point with this is that when you look how big this generator is and if you get the results of your study showing how the control or the tube design, stabilise this generator after disturbance within a second.
Can you imagine what force would be required to slow down this mass which rotates at few hundred revolutions per minute.
How...what force is needed to stabilise it to pull it back to a synchronous speed in one oscillation.
So this is something which we have to bear in mind as something which is physically impossible.
On the paper you can get results in the shape and form that you practically wish.
But in reality we are talking about real devices that are oscillating, that can not be slowed down instantaneously and held and kept in steady state without a huge force which often we do not have.
So always bear in mind that you are dealing with physical devices.
And these are examples of rotors both on the top left hand side is a salient pole rotor where rotors are attached to a drum of...made of typically laminated steel door.
And right hand side and bottom are rotors both, on the bottom slide we have salient pole rotor on the left and cylindrical rotor on the right.
And on the top right hand corner is a cylindrical rotor or the turbo generator which is made of solid steel.
One thing that I want to emphasise here before going to actual modelling even though this slide is showing the armature winding of the stator.
There are two basic types of synchronous machines.
One with salient pole and one with a round rotor as you know.
Salient poled machines are typically machines used in hydropower plants.
They are short...their rotors are short and thick with a large diameter and relatively short.
And they are mounted vertically with respect to the horizontal surface.
They...because being chubby if you like short and wide, they rotate at slower speed because centrifugal force is acting on the conductors which are the circumference of the rotor are proportional to distance from the centre and the speed.
So centrifugal forces will be very very high and they would tear rotor apart if the speeds are too high.
So there is a limit of how fast the rotor can rotate depending on its diameter.
And because of that the speed is to be low and we still want 50 hertz in currents and voltages produced and induced in the system, in the stator.
These rotors are with a larger number of poles.
So their speed is 500, 600 RPM which is obviously resulting in a larger number of poles.
On the other hand cylindrical rotors, rotors which do not have salient poles are used in turbo generators.
And they are if you like slim, they are long and thin.
Their diameters are metre, 1.5 metres typically, and the length can be as long as 6, 7, 8 metres.
They are mounted horizontally, and they're found in steam power plants, In thermal power plants and nuclear power plants.
And they're mounted horizontally, with respect to horizontal surface.
Because their diameters are small, they can rotate at much higher speeds, and they typically are either single or two pairs of poles machines, Meaning that their speeds are either 3000 rpm or 1500 rpm in 50 Hertz system, Or 3600 rpm or 1800 rpm in 60 Hertz systems, Depending on whether they have two poles or four poles.
So they can rotate at much higher speed, and have a small number of poles therefore, Compared to hydro generators which are very very wide, And therefore because of the centrifugal forces, They have to rotate at slower speeds.
Anyway, each of these, whether they are salient pole or wound rotor, They have two basic components.
These are in the rotor, as you know, Stator carries three-phase winding, A, B. C phases, And rotor carries filed winding. Field winding, And in addition to field winding we also have damper windings.
Now, when you look, the principle of operation of synchronous machines, So what actually happens there, The rotor in this case shown as a two pole machine, with a single pair of poles, The rotor carries wires, a winding which is called field winding, And that winding is carrying or it's supplied with DC current.
So because of that, using the right-hand rule, We can find out the North and South pole of that magnet.
But if the rotor is not moving, that magnet is obviously stationary.
Thanks to the fact that this rotor is connected rigidly with the rotor of the turbine, so turbine is forcing this rotor to rotate.
So what we have, we have a magnet now, that rotates inside the stator, And flux, the lines of flux that are those coming out of the north and south pole of the magnet, Are intersecting with the windings in the stator, And therefore electromagnetic induction takes place, And we have induced voltages and currents in the stator winding.
Now, three phase winding, which is spatially distributed along the circumference of the stator, carrying time-varying current induced by the rotating rotor inside the stator, This winding creates rotating magnetic field; And this is something, probably one of the greatest inventions of Nikola Tesla, at the late of 19th Century is, Explaining and understanding, Understanding and explaining the rotating magnetic field.
So this rotating magnetic field now, which is the consequence of alternating currents induced in spatially distributed winding, Result in another magnetic field.
So inside the air-gap between the stator and the rotor of the generator, We actually have two fields.
One, at least initially, is one is coming from the rotor, which rotates inside the stator, And the other is armature reaction, which is the field which results from the currents induced in the stator.
These two fields together combine and then inside the machine actually we have one field, Which is the sum of the fields coming from the rotor, And one, as the armature reactance.
So that field that exists in the machine is actually the one which magnetises the machine, Same as when we talk about magnetization of the core of either induction machines or transformers.
So what we have now is a fact that these two fields originally that combine into one resulting field, Are coupled depending on the loading of the machine, So if the machine is not loaded, then the currents in the stator are, if the machine is not loaded, so if there is open circuit stator, There are no currents; there is no way that currents can flow, in the stator winding. So there is no armature reactance.
So the only field that exists in the system is the field coming from the field winding.
Once some load is attached to the stator, Currents get induced in the stator and they create rotating magnetic field which now interacts with the original field coming from the field winding, And we have this resultant magnetic field in the air gap.
Depending on how strong these two fields are, And how much loaded the machine is, There is a slight lag of the stator field with respect to the rotor field.
That, the angle between the two, is something that we refer to as a power angle, and I will come back to that later on, In much more detail.
But now, what I want to say is that this damper winding, Which I said also exist on the rotor, They are typically mounted on the top of the poles, if we have salient poles, Or they are separate windings at that... mounted on the top of the field winding, And then connected there. So they are short-circuited.
They actually form, if you look at them isolated from other windings that exist on the rotor, which is the field winding actually, If you look, damper windings, they look actually as a squirrel-cage induction motor rotor.
So it's a short-circuited winding which doesn't have any source in it, And which carries the current only when there is magnetic induction in that winding.
So when do we have a case of magnetic induction in that winding? Under normal operating condition, the turbine is forcing the rotor to rotate practically at 50 Hertz, which is electrical 50 Hertz of course.
Now the induced currents and voltages in the stator result in a magnetic, rotating magnetic field, which rotate also at 50 Hertz.
So from the point of view of the windings, If you are sitting at the circumference of the rotor, You are rotating at the same speed as the magnetic field coming from the stator.
So the surface of the rotor is practically stationary with respect to magnetic field which was a result of currents induced in the stator.
So if there is no difference in speed between the circumference of the rotor and the magnetic field running around it, So there is no intersection of the flux, magnetic flux, And the conductors; so there is no induction in the windings on the rotor.
So there is no current induced in rotor windings during the synchronous operation.
Therefore, there is no current in damper winding, And there is nothing that these windings actually do.
The moment there is a difference between the rotor speed, which is the consequence of rotor being forced by a turbine to rotate at certain speed.
So as long as there is a difference between the speed of the rotor which is determined by the turbine that is forcing it to move and the speed of rotating magnetic field in the air gap which is a consequence of currents induced in the stator and the loading obviously of the stator, as long as the difference within these two speeds then magnetic flux from the rotating magnetic field will intersect with the bars of damper winding in the rotor circumference and there will be some induction of currents in rotor windings.
That includes both damper winding and field winding and then this damper winding which are designed in such a way that they offer low impedance and low resistance to magnetic motive force waves of fundamental wavelength but of harmonic frequencies, so they are designed to basically dissipate all this unbalance in two magnetic fields or energies in the rotor.
So they are actually dissipating induced currents very very fast and they take the initial disturbance on themselves, dissipate it quickly and stabilise machine.
So basically their main role is to dump or prevent oscillations of synchronous machines about the mean value of the angle and to carry with rotary safety the current induced during disturbances because the currents will appear in them only when we have difference in speed.
So damper windings therefore are essential for making sure that machine is stable major source of damping.
Now schematic diagram of the synchronous machine therefore is slightly messy here but it shows that we have three windings in the stator 'a', 'b' and 'c' obviously phases, we have field winding on the rotor and we have 'D' and 'Q'.
we're now talking about damper windings, actually we have only one winding physically but in order to represent that mathematically in more coherent way, we are talking about damper winding in 'D' axis which is the axis along the axis of symmetry of the rotor and damper winding in the 'Q' axis which is a axis perpendicular to that one.
Now why are we doing that? Because if you look this example of the salient pole generator, the magnetic flux originating at the rotor which goes from the rotor to the stator along the vertical axis of symmetry along the 'D' axis of the rotor, the distance between the rotor and the stator is much smaller in that direction.
So the magnetic resistance or reluctance of the air which is much higher than reluctance of the Iron that rotor and stator are made of, reluctance is much smaller in that direction.
So the coupling between magnetic fields of the rotor and the stator is much better in that direction and most of the lines of flux originating from the field winding actually will go along that way and then enter the stator.
Along the Q axis which is the axis perpendicular to D axis, the air gap between the stator and the rotor is much bigger.
So reluctance of that magnetic path is much bigger.
So fewer lines will go along that direction.
So we have magnetic asymmetry of the circuit actually and that's why we are separating it to D and Q axis.
Now you may think 'OK this magnetic asymmetry is obviously obvious for salient pole machines because we have a clearly non-cylindrical rotor.' In case of cylindrical rotors, one would think that this magnetic symmetry doesn't exist.
Well it does actually even though it's much smaller.
It is much smaller because the rotor is made of solid iron, it's a cylinder inside another cylinder so the distance between the surface of the rotor and the surface of the stator is constant.
However along the circumference of the rotor there are slots within which the conductors either field winding or damper winding are placed and these slots which are carved in the typically solid steel body are filled in with copper or aluminium conductors.
So along the circumference we have parts of the rotor which are not of equal magnetic permeability as the other parts.
Typically only two thirds of the rotor circumference are slotted with slots, with conductors.
The other third is not, is just a solid one.
So even though rotor is cylindrical, in case of round rotor machines there is still non homogeneous distance between the rotor and stator in different directions.
So we still can talk about 'D' and 'Q' axis asymmetry even in cylindrical machines even though this asymmetry is significantly smaller than in case of salient pole machines.
So equivalent circuit therefore for a generator is shown here and you can see for 'D' axis and 'Q' axis they are similar.
Similar in a sense that they have three branches.
One, the first one I'm talking about shun branches, the first one marked as 'L' 'a' 'd' is magnetising inductance effectively in 'D' axis or that would be magnetising reactance if you're talking about induction machines.
If you're talking about synchro machines it's called armature reactance in 'D' axis.
Then we have damper windings.
Now we have damper winding in the middle and then field winding.
Obviously both of them have resistance and inductance and in the field winding you can see a DC source.
On the left hand side 'L' 'l' is the leakage inductance of the stator.
Similarly for the 'Q' axis, so the axis which is perpendicular to axis of magnetic symmetry of the rotor, we have again leakage reactance and then we have magnetic reactance or armature reactance in 'Q' axis and then we have two damper windings.
So rotor is in case of cylindrical rotors, rotor damper winding in 'Q' axis is represented by the two windings.
This has been found as better representation to demonstrate better magnetic coupling in case of cylindrical rotors compared to salient pole rotors.
In case of salient pole rotors, the 'Q' axis representation of synchronous machines is without this second rotor winding.
So in case of salient pole, the third branch on the right 'L' to 'Q' and 'R' to 'Q' which represents second damper winding in 'Q' axis doesn't exist.
So for round rotor this is what we have in front of you is the equivalent circuit of the round rotor synchronous machine in 'D' and 'Q' axis for a salient pole machine the difference would be that 'Q' axis doesn't have the third branch on the right.
 
Synchronous Machine Modelling, automated transcript 018-10-12 ---  
LECTURER: 
Now, the key question is - how do we actually model? How do we come up with this equivalent circuit? When I talked before about the design, about the physical design of this synchronous machine I said that the stator has three windings which is A, B and C phase.
And the rotor has two basically windings, one is field winding carrying DC current and the other is damper winding which doesn't carry any current in static state.
This is the fact, this is what we actually have.
Now the question is when you write all these equations for the stator and a rotor, and they are shown on the right hand side you can see that there are actually seven differential equations.
For we are talking about cylindrical water machines.
So we have three equations for voltages in A, B and C winding and then we have equation for field winding with index f.
And then we have damper winding in d-axis with index D.
And then we have damper windings in q axis with indices q1 and q2.
Now in case of salient pole machines as I said that the last equation the one which starts with Vq2 equals and so on that one wouldn't exist.
So anyway let's talk about round of machine.
So we have seven equations which describe the electrical circuits we can find on...in the synchronous machine.
Now, the problem that arises here is design of the machines.
Machines, these are four options shown diagrammatically of possible designs of the synchronous machine.
So we can have a generator which has round rotor and round stator top left corner.
Or we can have design at the bottom right hand side corner which shows salient pole rotor and salient pool stator.
Now looking at these four options, I'm not going to discuss all four of them I will just focus on these two.
If you look these two different designs you can see that depending on the design of the stator and the rotor the distance between stator and the rotor Ion parts is different.
In case of cylindrical stator and cylindrical rotor you can see that the distance between the surface of the rotor and the surface of the stator is constant.
So whichever way the rotor turns there is no change in magnetic coupling between the two.
In case of the salient rotor salient stator design which is bottom right hand side corner you can see that depending on the position of the rotor inside the stator there is a different coupling.
So both leakage reactors on the rotor and stator depend on the position of the rotor.
And then depending on the alternative designs, either design with a round rotor and salient stator or salient pole rotor and cylindrical stator we have a situation where reactances or inductances of stator and rotor depend on the position of the rotor.
So that's unfortunate because if we look these equations and then if you look at the equation for the stator we see that the voltage in one of the stator circuits is obviously result of voltage drop in resistance and then derivative of flux.
This flux then derivative of flux with respect to time this is the first equation on the slide shows that we have actually to derive to find derivative of inductance because it depends on rotor position and derivative of current.
So when you look that equation, this becomes a differential equations which has time varying coefficient.
So different times during the rotor rotation we have different coefficients in differential equations.
It's very, very difficult to solve.
Because of that you need to exclude this rotation in addition to other transformation that are shown on the previous slide in this slide here.
Because of this dependence of inductances on rotor position which results in differential equations with variable time varying coefficients a transformation was introduced by Mr Park in 1929 called widely known as Park's transformation which actually converts physical A, B and C phase windings of the stator.
It maps them in d and q components of stator variables voltages and currents and fluxes which are fixed to the rotor.
So now we are kind of making stator windings to rotate at the same speed as a rotor so there is no dependence of inductance either stator or rotor inductance on the position of the rotor.
This transformation obviously results in new term which we can see in the second line on the slide with equations where we have a term which is derivative of angle with respect to time times flux.
So when we look at that this is now speed voltage.
Sometimes this component is referred to as speed voltage because derivative of angle multiply by flux is effectively voltage.
So it's called speed voltage because derivative of angle with respect to time is actually speed.
So this results in new form of voltage equations for stator where inductance is not dependent on the position of the rotor.
So we get a differential equations with constant coefficients.
If you look at this equation now we have this speed voltage which is delta theta over delta t times l new times i new, this is the speed voltage introduced by this conversion of A, B, C winding into dq not if you like winding.
There are three components because you are mapping three windings A3 faces ABC into different reference frame which has dq and zero component.
The zero component is important to remember the zero component is not actually positive negative and zero sequence component.
It's similar to zero sequence component as it is used only in case of unbalanced faults involving the ground and the quantities which feature in that equation are typically...
are the same as those used in zero sequence studies, but this is not zero sequence component.
It's just called zero because of the similarity with zero sequence component.
So the middle bar bit is a speed voltage and then in the bit on the right which is L new delta i over delta t is a part that we had problem with before but not anymore because this L new now is not dependent on the position of the rotor, so this part transformation actually solve the problem and simplify the model in a fact as it resulted in set of differential equations which are much simpler to solve.
Now these set of equation now complete model of the equation for a synchronous machine is shown on the left hand side there are differential equations and on the right hand side are corresponding coupling algebraic equations.
And it has the complete model has...this is the complete model for a salient pole...for round rotor machine, cylindrical rotor machine.
And this complete model has as you can see nine equations.
Because for a stator zero sequence component is included, Then we have d, q and nought for the stator, top red rounded equations.
Then we have a rotor which are four equations field winding, damper winding in the x-axis and damper winding in the q-axis one and two.
And at the bottom we have two equations which describe electromechanical or swing equation.
They are shown here as two equations that are as one as we discussed before because originally that was second derivative of angle equals one over two agents.
And now after substitution of first derivative of angle with speed we ended up with two first of differential equations that's why the electromechanical or swing equation appears here as two equations.
So we have nine equations.
These nine equations are used to describe transients.
These are equations which are the full model for describing dynamic phenomena of any type in synchronous machine.
Now because most of the time and we are talking about system stability, we do not consider asymmetrical behaviour of the system because for a stability system is basically considered to be symmetrical.
Zero component for the state or disappears.
So the full dynamic model basically becomes the model which has eight equations without zero component for that stator.
Zero component is only used when we are talking about studies of faults.
Asymmetrical faults involving earth which is single line to ground faults and two lines of ground fault.
For all other purposes that equation is for a system dynamic studies, for stability studies that equation is not used.
So we have two equations for the stator, four for the rotor and two electromechanicals.
So altogether eight equations describing system dynamic synchronous machine dynamics.
I'm not saying these are the ones that we use to represent synchronous machine in conventional system stability studies I'm saying this is the model of which describes full dynamic processes or in synchronous machine.
Now that can be further illustrated by a slightly different equivalent circuit compared to ones we had before.
This is in a way time decompose equivalent circuit which actually shows how machine behaves during different stages after disturbance.
So two components which are always present are first on the left which is a DC excitation voltage.
And the last on the right which is armature resistance and reactance which is stator component that the black rectangle on the right.
The three components in the middle are describing basically transition between the disturbance and steady state.
Initially after disturbance the machine is described with red bit, red rectangle just sub-transient operation.
Few tens of milliseconds later that process disappears.
So the behaviour of the machine is driven by the middle part which is transient operation.
After about seven to 10 seconds this process disappear and then machine continues to be described by the steady state equations which is steady state operation and a blue rectangle which is only armature reactant.
So, this is equivalence circuit with respect to transition in time.
So at any given time machine is not represented by all of these three.
At the given time after disturbance only one of the three dashed line rectangles stays in depending where are we after disturbance.
For sub-transient operation typically five to six cycles after disturbance.
Eventually up to about 200 milliseconds typically not longer than that.
The first rectangle applies.
After that for next few seconds after ten seconds the second rectangle applies.
And then after that when the transients in the field winding disappear then we have an operation with...in steady state which is the blue triangle where only armature reactance is represented.
So in steady state coming back from the previous slide this one as we can see we have a field winding which has a DC source EFD shown here which is the electromotive force in the field winding.
We have armature reactance, we have liquid reactant stator.
And this is the full representation of the synchronous machine in steady state.
Now when you look voltage drops in this circuit.
So the source voltage EFD is shown in the phase diagram on the right.
Then we have a voltage drop due to the magnetization of the machine.
This is the voltage drop depending on current that machine is carrying, depending on the load.
And armature reactants, reactants or magnetising reactants of the machine.
So this is a first voltage drop then after that voltage drop we come to phasor E the green one in the middle.
So this would be effectively the voltage that we have if you like at the start of the stator windings.
Obviously stator winding has certain inductance and resistance which is not shown here.
And then we have voltage drop across stator winding.
And then finally we come to voltage V which is the terminal voltage at the terminals of the genus.
This is the voltage if you actually measure.
So when you look at this so what we have.
EFD is the voltage that we apply practically to the machine through a DC excitation.
And V is the voltage to get out of it.
Obviously some of it is lost while if you like this voltage is making a transition from the source 'till the end of the machine.
The differences between these two phasers is our power angle.
This power angle effectively is the angle between the magnetic fields that exist in the generator.
Because in typical operation this angle is small enough.
We are talking about well, small enough is a questionable statement but it's about 40 degrees, less than 40 degrees in steady state operation for most of the machines.
So, this... is the angle between two magnetic fields which is not entirely correct because even though we have two magnetic fields initially inside the machine, one originating from the rotor and the other from the rotating magnetic field, these two combine into resultant magnetic field as shown in the diagram as well, which is marked as Fr, the horizontal dark blue vector or phasor on the left hand side.
So this field is the only field that actually exists in the machine even though it is a combination of the armature field, which is shown along the current A, and excitation field coming from the DC voltage is shown to the left.
So this resultant is the combination of the two but this is actually only field that exist in the machine.
So angle delta effectively, is the angle between F resultant which is the blue one, and FF which is the green one.
So effectively it is the angle between resulting magnetic field and magnetic field from the excitation winding.
However, when we talk in order to understand what is actually going on in the machine, we are often talking about this angle as being the angle between the stator and the rotor magnetic field.
Because the angle phi shown in the diagram between vector phasor as E and V is very, very small.
Liquid reactants Xl, is of the order of 0.1 to 0.15 per unit, while Xa is armature reactants of the stator and that typically is between one and two.
So we are talking about these two vectors Xa times i and X1 times i, being different about ten times.
So Xai is about ten times bigger than X1i therefore angle phi is actually much, much smaller than angle delta shown in this phase.
So the angle between ENV is about ten times smaller than the angle between Efd and E.
Therefore, we often talk about delta being angle between two magnetic fields.
So if the machine is unloaded, there is no current in the stator, so current i is zero.
If current i is zero, then there are no voltage drops.
Xa times i or and X1 times i, so voltages Efd and V are the same.
So the excitation voltage which we apply to a field winding is the one that we see at generator terminals.
As we start load the machine, as the loading is higher, the current i is bigger voltage drops Xai and X1i becomes bigger, and these two vectors Efd and this start to separate more and more.
So the angle between V and Efd increases.
Therefore the more loaded machine the bigger power angle is.
Because the angle between Efd and V is our power angle.
And then once that angle reaches certain value, the machine may lose the stability and you know that already so there is no need for me to hide it.
Once this angle is 90 degrees, we lose the stability.
We'll come to that in a few slides.
Now, steady state model, therefore, because everything is stationery, there is no variations we can neglect all differential equations and then we have very, very simple algebraic equations that describe this circuit which has one source and one reactants sorry resistance and reactants or one impedance.
Now the problem of this power angle, an angle as such is best described using power angle curve.
Which you can see here on the slide and we can see that angle changes from zero to a certain value as power increases.
So there is the horizontal axis here should be delta not d, so this d is actually delta and p as you can see in the next slide is pi and p/2 is pi/2.
So maxim is here is at 90 degrees, this is pi which is 180 degrees, and d is not this delta.
So this is power against angle of the generator.
So as the mechanical power coming from the turbine which is a horizontal line doesn't depend on the angle, is a constant delivery of power from the turbine.
As long as that power stays constant, we can have intersection between power coming from the turbine and power delivered by the generator.
Now you can draw parallel here between this graph and the graph that I was...slide that I was talking about before when I discussed voltage stability.
In the case of voltage stability, Pm here was actually Qs.
So what the system can give.
Here it is what turbine can give.
In the case of voltage stability, Pe shown in this slide, was Ql.
So reactive power that load requires.
So if we look at these two from the same perspective, we can see that under normal operating position or condition, we have two intersect points between what system can deliver and what load or system demands.
And these two operating points can be either stable or unstable, we'll look at that a little bit later.
As the system delivery goes up, so as the Pm increases, we may reach a point where we have only a single common point and then if mechanical power is much higher than what the load is, so if the load is much lower than what the system is delivering, we cannot have an operating point at all.
So system cannot operate if there is no intersection between what is delivered by the turbine and what the load requires.
So this is the power angle curve, as we know it, as we're going to be using it in reality however that curve is slightly different, it's not really sine wave, there is the fact obviously of the resistance of the stator which was not accounted for, when this curve was developed, and there is a fact also of saliency because there is not purely symmetrical circuit.
So because of that as you can see when both of them are included both saliency and effect of the resistance shown at the right hand side.
There is slight shift of this maximum value and angle at this maximum value of power that machine can deliver is happening.
So in our theoretical studies, the studies we are going to be talking about here and which are good for all practical purposes, we refer to a stability limit as 90°.
In reality however, this 90° is not 90°, more 85°, 86°.
There are a few ° the peak of the power occurs at angles which are few ° smaller than 90° and this is because of the saliency illustrated in the left and state of resistance illustrated on the right.
But this is important to remember because if you are operating at 80°, you may think I am 10° away from stability limit.
While in reality, you may actually not be because the actual stability limit is lower than 90°.
It's important distinction to remember.
The final thing I want to say about the...
this section when talking about realities and design of synchronous machine is something which we are not typically referring to when discussing system stability but it's very important to mention because this defines physical limitations that synchronous machines has.
Now this physical limitations are incorporated in something which is called generator performance chart as you can see on the slide in front of you.
These, I'm not going to discuss it in any detail.
There are many books and many sources that you can find to read more about it.
What I'm trying to say here with this graph, there are physical limitations of any device, including synchronous machines which we must obey.
This physical limitations are imposed basically by design of the machine, by materials used and by interactions of this material.
So depending on how big physically the machine is, what type of iron is used, what type of material for conductor is used, how thick this conductor is, how loaded they are.
We will have physical limitations of what that machine can do without being physically damaged.
So we have limitations on maximum power we can deliver, a minimum power that can be delivered by the machine in order to avoid either machine stalling or being overheated.
About maximum current, it can carry in stator or rotor binding before this start to melt or become unnecessarily hot and so on and so forth.
So there is area here marked by the thick red line which shows possible combinations of real and reactive power that synchronous generator can deliver.
So we quite often talk about operation with power factor 1.
Power factor 1 means that reactive power is zero and the all power produced by the machine is real power.
That is clearly possible because we can operate along horizontal axis along P axis because the only points inside this...whatever the shape is, multiangular surface... for a lack of better word...
So only the points inside the red area are visible so we can have a point on the horizontal axis.
On the other hand, we cannot have a point on Q axis because there is a minimum real power required for machine to rotate so we cannot have operation with power factor zero.
It can be very small but never zero because of the minimum real power the machine has to deliver.
Also another very important thing that we have to mention is the saturation of the synchronous machine.
So saturation is something that naturally exist in all materials and this is something that you probably learn in your preschool education, pre-university education I think in physics.
So depending on the qualities or magnetic properties of the material used, there is a point magnetic material in particular because this is what we're talking about here.
We cannot anymore have linear relationship between the strength of magnetic field and the current applied.
So instead of as this diagram shows is that of getting more and more flux or magnetic inductance.
If we increase the current in the field binding, there is a point when this characteristics starts to bend and then to saturation.
So further increase of current in the field binding will not result in increase in magnetic flux and therefore the voltage at generate terminals will not go up.
This point where the curves starts to bend and ceases to be linear and becomes saturation curve, is typically at about 0.8 preunit of terminal voltage.
So when we start increasing the field current in the rotor of the generator, voltage increases and at the point almost linearly.
And at the point when we reach 0.8 of terminal voltage, further increasing current is not resulting in linear increase in voltage.
So we have increased current much more for less increasing voltage.
So this is the fact that the materials start to saturate since all machines operate with terminal voltage one or even slightly higher than one in order to provide voltage support to the rest of the system.
Machines practically always operate as saturated.
Therefore, parameters that we should be using in studies with machines are saturated parameters and this is one of the way of representing saturation in both D and Q axis.
And these values are typically lower than unsaturated values.
They are between 10% and 20% lower and obviously whatever quantity we calculate using reactances, saturated reactances, and if this saturated reactances appear as a multiplier then the corresponding quantity will be smaller.
Or if they appear in the denominator as dividing something, then the quantities will be higher clearly.
So this is important thing to remember because when we get the parameters of synchronous generators, manufacturers typically give both sets of parameters, saturated and unsaturated value.
If we want to be absolutely sure we're using the right parameters for the studies, it will be much more proven to use saturated values rather than unsaturated because this is what would represent reality much closer.
 
Synchronous Machine in Stability Studies, automated transcript 018-10-12 ---  
LECTURER: 
Now, once we have defined or not really define but mention the generated performance chart which actually defines the feasible area of operation of synchronous machine so how much in real and reactive power it can deliver at any given point, and mentioned saturation as another physical limitations to be aware of what parameters should be used and as you saw in one of the previous slides there was a table showing typical parameters for synchronous generators, typical values of reactances and inductances, and time constants and inertia constants and so on.
We have to talk about practical application of these models in stability studies because what we are talking about here is power system stability.
So the full model, the full generator model for describing dynamic processes inside the generator has eight differential equations.
Two for stator so voltage in d and q axis we said zero component is neglected because we are talking about symmetrical operation and zero component applies only if you talk about short circuits that involved the Earth.
So there are two equations for stator.
There are four equations for rotor, we are talking about cylindrical rotor.
And there are two electromechanical equations.
Altogether eight. Now, the key point here is this is a full dynamic model, do we need that model actually for power system stability studies and remember we are dealing here with a stability rotor angle stability which involves electromechanical oscillations, electromechanical oscillations lasts within a second and few seconds so these are transient processes which start about a second after disturbance.
Differential equation that the Pe and mathematical model the synchronous machine for the stator.
They describe electromagnetic transient stator bindings so these processes will typically be finished before the movement of the rotor of generator starts so we can easily neglect these processes and simplify the model and this is exactly what we are doing so instead of having differential equations as for voltages in d and q axis of the stator we neglect derivatives from those equations and we use algebraic equations.
That move results in the model which has two differential equations less.
Before we see the model, let's see what the consequences.
This slide shows with solid lines actual behaviour and dash line is when we neglect stator transients so what you can see here is torque and stator currents and they are by all means very, very different if we include or neglect stator transients.
However, if you look the timescale the timescale shows 70 milliseconds.
So we are talking a very, very short period of time.
So for a very short period of time we have a big difference between the two but since we are talking about process which last from a second to several seconds, afterwards, after first second you can see that there is practically no difference and if you look now slightly longer timescales on the left hand side is 0.3 seconds so this is the difference in speed and on the right hand side is two slightly more than two seconds is again rotor angle so what we can see, we can see that with values which neglect stator transients.
We get worse performance.
In other words, with stator transients included performance would be better.
So the fact that we are neglecting stator transients we are making an error, a very small error, but this is conservative error so our results will always look worse than they actually are so this is a good error to make.
The fact that we are neglecting stator transients we reduce the order of the mathematical model from eight down to six.
So the set of differential, first all differential equations, on the left hand side in the red rectangle represent full dynamic model of synchronous machine for system stability studies.
So it has six differential equations which is two more then the model before which explains, which describes all dynamic processes inside the synchronous machine.
So the previous one includes electromagnetic transients which are not necessary for system stability studies and this is the model typically used in all commercially available packages when talking about system stability.
Now the other thing is this is six equations, fair enough.
In case of salient synchronous machine their number equations would be five because as I said before the equation for rotor which includes second winding in q axis would be neglect in that case so we would have in the rectangle, in the red rectangle we will have equation for field winding, we will have equation for damper winding in d axis one, we would have equation for damper winding in q axis one, and then we would have two electromechanical equations.
The equations we described as processes in damper winding in the q axis number two would have been neglected in case of salient pole machines.
Now, the next simplification is so what happens if you don't have damper windings.
If you have machine with no damper windings obviously equations use to describe process in damper windings will disappear and the model would be reduced by further two or three equations depending whether we are talking about salient pole or round rotor machine.
In that case, we end up with a model which has only three differential equations and this is the model which now describes transients in the field winding only and electromechanical equation swing equation.
This is the model which is necessary to be used if any voltage control is to be modelled.
Because if you model any voltage control that their fact to voltage control will be inserted into the model through this field equation through the efd = Rfd i fd +1/omega0 p times derivative of flux.
P stands here for derivative with respect to time.
So this model three differential equations is necessary if the studies are to be carried out which do not assume constant excitation.
However, in the many studies we can actually assume constant excitation. We can assume that the variation in the excitation voltages is very small and that they do not have effect on behaviour, on behaviour of the rotor predominant in rotor movement.
So in that case, we can reduce the model further, to a model of only two, with only two differential equations, and this is called, often referred to as classical model or constant flux linkage model, as it has only two differential equations per machine.
Now we dropped, if you've noticed, from the model of eight differential equations to only two.
This is significant reduction, considering the fact that in one system, like European transmission system, you may have five, 6,000 generators.
So if you reduce the size of the model, by six equations per generator, you basically reduce the size of the model by 36,000 differential equations.
So instead of having, for example, for the European system, a model with, I don't know, six *eight is 48,000 differential equations, you can drop down to model with 12,000 different equations, significant reduction, much simpler to handle, much, it can be handled much faster.
And, and, all calculations will be simplified.
Now, the question is, these simplifications, how they actually impact the results of dynamics studies, this is example, which shows how the power variation will, will, will look like depending on what type of model we use.
And the four slides in the left hand side, starting from the bottom up, are performed with eight, six, three and two differential equations or different stages of simplification that I described before.
So as you can see at the bottom, we have, and this is magnifying right inside, the red curve shows very fast transience, during the volt, and immediately after the volt is removed.
After that, after the first, 200 milliseconds, because the fourth was applied at one, and then removed at, 1.2, so 200 milliseconds later.
Sorry, a hundred milliseconds later.
So after 200 milliseconds, you can see that the red line oscillations completely disappeared.
After that, the, the, the four curves go together.
So, looking further, if we are not interested, in a period in full studies, which is, electromagnetic studies of the order of, tens of milliseconds.
We can safely neglect first two equations, differential equations in the model, and dropped down from eight to six.
Now comparing eight and six, these are red and black lines on the left hand side.
They practically look the same.
And if we are reducing the model further, we can see that the simpler the model is, the more oscillation it shows.
Which means that if we use, classical machine model.
And if they make conclusion, the system will be stable.
It is very likely that real system will be stable.
Even more stable, because the results obtained with simplified model are, making error on, on a conservative side.
On the other hand, on the other hand, even if the results with simplified model shows some, borderline stability or even instability, this is still not necessarily unstable system.
The biggest difference, it can be seen from this graph, is difference between top, which is purple, second or classical model, and blue, which is the third order model.
This is the biggest difference which is, the fact when we moved from third order model, to the second order model.
This difference, is predominantly caused by the fact that in this case, the.. no attention was paid to the fact that field winding and damper winding in particularly were neglected.
If we look, several next slides, you can see there is different responses depending on the way, how the swing equation is modelled.
Swing equation, which as you remember, has difference of electrical and mechanical torque on the right hand side, and the acceleration is determined based on this difference.
Obviously what's missing there is, some damping effect which is coming from the field winding.
Originally, this equation should have included, effect of damper winding.
That effect is naturally built in, in electrical power component when damper windings are modelled.
If they are not modelled, then obviously this cannot be present.
Therefore, there is damping coefficient, which we will discuss in the next session, when I start talking about, small disturbance stability, damping coefficient or damping constant, which has to be included in simplified in, in classical generator model.
If, we want to get results, which are very, very close, to those that will obtain with dynamic model, with six differential equations.
So the only, the biggest difference is actually coming from the, the fact that we neglected damper windings and we removed their contribution to reducing oscillations, that can be artificially added by changing the value of, damping constant, which appears in swing equation.
But I will get back to this a bit later on.
Apart from standard parameters, when we look at the equivalent circuit that we saw before, and discuss before.
These parameters, are parameters of electrical circuits.
So they are resistances and reactances.
This is not something which is, very useful for people involved in power systems stability studies.
Because in power system, people are not actually, talking that much about resistance and reactances, we tend to talk more about voltages and currents.
And some time constant.
So, the way how generator parameters are typically provided, to facilitate power system stability studies, is not in the form of parameters of the current circuit.
It is rather in the form of, parameters which are, which are relevant to this alternative, equivalence circuit.
They also show that the beginning, which involves sub transient and transient values, and some time constants.
And these values, are listed here.
So these are the values.
Transient and sub transient inductances, or reactances.
They are shown here as inductances in per unit, but again, because the scaling within inductance and reactance is through synchronous speed.
And in per unit this speed is one. So per unit values of, inductance and reactance are the same. So wherever you have here L it can be equally replaced by x as these are same values in per unit. So here we have parameters for different stages of system or generated performance following a disturbance starting from sub-transient, transient to steady state.
Sub-transient quantities are shown with the second double dash values.
Transient with a single dash so T'q and that will be for example transient time constant in q axis and T2'q is sub-transient time constant in q axis and correspondingly we have values for inductances in d and q axis.
Now these values obviously then can be further developed that's why we have full equations for time constant so this time constant actually define duration of different stages following the disturbance.
Sub-transient, time constant defines how long sub-transient period lasts.
Transient time constants does the same for a transient period and then we have Ta time constant which is basically defines how fast the DC component and use DC component in the stator of the synchronous generator is dissipated.
Now, the other confusing thing with these time constants is that we have some which have subscript zero and some don't, so these with subscript zero are referred to as, for example, sub-transient open circuit time constant in d axis or transient open circuit time constant in q axis and so on and so forth.
The ones without zero in the or not in the index in the subscript are simply transient or sub-transient time constants in d or q axis whatever is the applicable value.
The difference is between the two is that open circuit time constants are developed based on unloaded machines so when the stator is not connected to the system and this clearly defines the process in the machine which do not involve stator contents, they do not involve stator liquid reactions because there was no current in that circuit.
Now, transient and sub-transient quantities which do not, which are not open circuit are usually affected in short circuit time constants.
They are relevant for short circuit studies because in that case depending when the short circuit is, that portion of the network, so stator reactances plus the portion of the network I've taken to account to derive these time constants and then apply them in equations for short circuit currents.
Most of the time, most of the time manufacturers do not give those values instead they give open circuit values and then the conversion between the two can be done using the formulas provided here.
At the bottom, not to confuse you, at the bottom are some options some options how the negative sequencing pins off the synchronous generator can be calculated in different ways depending on the type of the folds it is used for.
This is as I said not relevant to our syndynamics studies but because I'm taking about transient, sub-transient contents you may as well have this information for short circuit studies in single generators. So depending on the type of the fold that you want to calculate time constant for they are different values how negative sequencing pins is calculated from most practical purposes negative sequence in pins is calculated using their formula above which is simply average value of the positive, sorry, of the values in d and q axis so if we have d and q axis sub-transient reactances then a negative sequence of the machine is calculated as the average of the two and then used to calculate time constant Ta which defines how fast DC component in the stator disappears.
Now, these are equations which students often asked what should I do with them, how can memorise all of this they look very complicated well they actually do but the good thing about them is you do not have to memorise them it's enough to memorise equivalent circuit and then you can derived them from the equivalent circuit so if you look the equivalent circuit of the generator here, examples are shown for calculating sub-transient reactance in d axis, transient reactance in d axis and then sub-transient, transient time constant either open circuit or short circuit here in the d axis so if you look the top figure on the left side which is part, which is the equivalent circuit in d axis for calculating transient, sub-transient reactance in d axis so what does it mean? What I am talking about is if you are sitting at the system site and if you look in the machine so what do you see? What is it that machine represents to you as a system looking at it from outside? So what can you see? We can see leakage reactance LL of the stator and then we see three reactances in parallel.
One is magnetising reactance or how much it reactance in d axis then we have dumper winding reactance and then we have field reactance.
So sub-transient reactance in d axis is exactly equivalent reactance of the generator that the system sees immediately after disturbance.
And then obviously calculating that you can get this long sausage-like formula.
This will be valid only for first 100, 150 milliseconds.
After the transient, after that process is gone, after 200 milliseconds all the currents initially induced in dumper windings will dissipate.
They will disappear because of the resistance and reactance of the dumper winding, they will disappear within about 200 millisecond.
So what happens, 200 seconds - milliseconds, 200 milliseconds after the fold is that equivalence circuit now changes so we're going to second equivalence circuit so the dumper winding branch disappears.
So we continue to look into the machine but we do not see dumper winding branch anymore.
So what do we see now? We see leakage reactance, we see magnetising reactance in d axis and then we see field winding reactance so equivalent reactance for this circuit is obviously LL plus parallel connection of Lad and Lfd cell the transient reactance changes.
If you continue looking at the machine after some five to ten seconds when transients in the field winding disappear then the branch Lfd will disappear from the figure as well so what you will have will have only Ll plus Lad which is a synchronous reactance of the generator. So this is how simply by looking into the circuit you can derive all this equation whether for d axis or for q axis and understanding of the process that are happening in the machine.
Similarly for time constants if they are talking about sub-transient time constant, open circuit time constant in d axis that is something which is happening in damper winding.
We understood that sub-transient process is associated with damper winding.
So if we position ourselves in the damper winding and look outside from the damper winding.
So what do we see? We see a time constant which is always define as L/R.
You have to be careful here when calculating this values for time constant all the quantities in these equations are given, on the slide, are given in per unit which means R and L are in per unit so T time constant will be in per unit not in seconds, to get it into seconds the denominator should not be one, it should not be R, one day it should be omega * R1d.
So in order to get these time constant in seconds these values calculate using the formula shown here should be divided by omega which is 3.14.
So looking at the sub-transient time constant in d axis opens second time constant so if we position ourselves on a damper winding and look outside from it time constant would be equivalent reactance that we see divided by resistance of that winding so resistance is easy that's R1d and reactance would be what it would be...
L1d connected in series with parallel connection of Lad and Lfd.
Obviously, leakage reactance of the stator is not included because stator is open circuited and there is no current going through it.
If however we have short circuit in stator then there will be current in the stator and then sub-transient time constant in d axis of short circuit stator would be very similar to the one before except that now we have reactance of the stator connected in series with parallel connection of three reactances not with two as before.
Now I use here interchangeable reactance and inductance because as I said reactance and reactance when presented in per unit have the same values.
So the point of this discussion is that you do not need to memorise all these equations you simply have to go through equivalence circuit and to think about the process that happening and based on that it's easy to derived these equations then that reduces the possibility of making an error because if you want to reproduce the equations completely you have to remember whether it's a 1d, 2d, 3d if in case when you are drawing the circuit yourself you can name them whichever you want you can put whatever symbol you want wherever you want and then when you derive them you can explain what each of the symbols is referring to them have to use the notation as used in this slide or in similar slides from different sources.
There are two or three different ways of actually that have been used traditionally for denoting particular values so for example for damper windings you either have notation as here where you have number one or two and then small values, small letter for d and q.
You have notations where instead of one, letter k is used so for example, damper winding in d axis would be reactance of damper winding in case for example xkd instead of x1d and damper winding reactance in second, q winding would be xkkq.
There is another notation where instead of small letters capital letters are used and so on and so forth.
So these are three most prevalent ways of representing these quantities but as I said as long as you know how to produce equivalent circuit and how to derive this values based on the circuit you don't really need to follow any notation you can invent your own.
Now, once we define these sub-transient and transient values and corresponding time constants we can then use them to develop alternative models of synchronous machines.
The previous models if you remember either simplify the full dynamic model involved derivatives of flux and they were based on currents so you typically had a voltage recoils, a voltage drop on resistance plus some derivative of flux times current.
Now that is not really the way how power system engineer thinks about - think about devices.
This is the way how people who work in the area of electromachines described devices because they are interested in electromagnetics and magnetic fields and currents, fluxes, and so on and so forth.
Power system engineers as I said before mostly think in terms of log, fields, and current so the model of synchronous machines in slightly of different form would be much more useful to them than those involving derivative or fluxes. That's why they have these alternative sets of models which.. or model.. which involves only currents and fluxes so E is a voltage and I is a current and the rest are normal reactances.
Now, before in this model we have transient and sub-transient values of a time constants and voltage is in reactance's that's why we needed this conversion that we discuss in the previous slide from conventional equivalent circuit models to the models which are more suitable for this alternative representation of synchronous machines.
So in conclusion known to facilitate power system studies are models of synchronous machines which are more voltage and current than current influx oriented are needed because of that parameters need to be adjusted to.. well to be derived, alternative parameters have to be derived based on the parameters and circuits and that's why we ended up with a model like this which is the model by the way widely used in all commercial level with packages, I think that there is no commercial level package for power systems stability or any type of power system studies where this type of model is not used where instead of this the model of influxes and currents is used.
 
Modelling of Turbines and Governors, automated transcript 018-11-7 ---  
LECTURER: 
The next device, the next regulator control.
They're going to talk about, is turbines and governors.
Similarly as extension system which consists of a controller and actual physical device, exciter, that regulates the voltage.
We have similar setup or equivalent setup that controls the speed of generator, these are the turbines and governors.
So, turbine is the primary or is something which produces that mechanical torque which appears to which the generator rotor is attached.
And then we have a regulator, which is basically controller that controls the turbine, the speed of that, of the movement.
Now, turbines can be different.
Can be hydro turbines, can be steam turbines, depending on the type of the turbine.
We have different modes of turbines, these modes are particularly complicated for steam turbines which can be very big machines.
In excess of 30, 40 metres in length.
And there often we have multi stage turbines, high pressure, intermediate pressure, and then several stages of flow pressure turbines.
So when they are put together, it becomes a very big rotating machine, in excess of 30 metres.
And then when you add to that, say steam generator rotor which can be on its own, about 7 to 8 metres.
So, we are talking about a device it can be as long as 50 metres.
So, that's why steam powerplants, they have very, very long and reasonably thin machinery.
Anyway, so in addition to steam, and hydro turbines, we may have gas turbines as well.
And in recent times obviously, we have wind turbines.
So, they are there too as a prime movers, to use different type of energy whether it's wind, steam, heat or nuclear.
Energy to produce mechanical movement.
Their speed is regulated by another controller which is called governor.
Now, the setup of the turbine and governor system is similar to one that we had for excitation system, except that in this case, we do not measure the generator terminal voltage, we monitor its speed.
So, speed is controlled and compared with the reference value.
If that reference value deviates from the set point which can be either 1 per unit or a point setup by automatic generation control in order to maintain the frequency in the system that sometimes the signal can be different, so the speed has to be increased or reduced to balance the frequency in the system.
But anyway, whatever the reference value is, if that deviates from the value you had at the given moment, then the speed governor sends a signal to different sets of valves and gates to open or close, which means to let more or less working fluid, water, steam, gas into a turbine and then as a consequence, turbine will increase or reduce mechanical power and therefore regulate the speed of the generator.
There are as I said, different types of hydraulic turbines and steam turbines and as I mentioned only for steam turbines, they can be quite elaborate models because of their sheer size and mechanical properties.
And then there are some models, typical models and parameters given for a steam turbine governing system.
One thing that is very important to mention here is that governors are typically not considered when power system dynamics studies are performed and when stability of the system is discussed.
Electromechanical stability, mechanical oscilliations, rotor angle stability.
Because traditionally, governors were prevented from reacting as fast as they can and some of them were slower in the past because they were not digital devices, today they are so they can respond much, much faster.
But even when they could respond fast, they were prevented from being so because people in charge of these governors, didn't want them to react to minute or rather small changes in speed.
This can be justified from the point of view of protecting the device and therefore wear and tear of the device and you want to maintain your governor, you don't want it to perform unnecessary actions.
On the other hand, it has been shown in many studies in the past that if the governors were allowed and obviously turbine speed regulating loop.
If it was allowed to participate in regulating the speed, not only after very large disturbances but too thinly.
Then much better damping of the system could have been achieved because in case of PSS, if you remember the Block diagram, PSS was shown as stabilised.
It was shown as part of the excitation system.
So, whatever control action PSS might have produced, it could go through the same control loop as the action that excitation system would produce.
So these two would obviously, if you want, compete for attention of the exciter and then the result and change in extension voltage would be in a way, a compromise between the requirements of PSS to control speed and the requirement of extension system to control voltage.
So, the resulting effect would be sub optimum.
If we could use governors to regulate speed and exciters to regulate voltage only, then first, for the voltage control point of view, there wouldn't be a competition between PSS and exciter whose action will take priority and based on whose action the voltage and generators or speed or the rotor would be controlled because PSS would not be necessary to be included at all at that stage.
And then on the other hand, the regulator would control the speed.
So, we would have decoupled control of terminal voltage or speed of the machine which will be beneficial to both to both control variables.
The problem with that is as I said, is that it would require much more frequent operation of the governors, opening or closing the valves which is something that people working in power plants and being responsible for that mechanical part of the aggregate or the unit, they were not very happy to do that.
And this is all what you need to know at this stage about turbines and turbine control because we're not going to go into models.
As I said in most of the studies, they're not even used in any shape or form nor represented in system stability studies.
 
Modelling of Transformers, automated transcript 018-10-12 ---  
LECTURER: 
The next component that we are going to talk to will be lines and cables.
Again, this is another area which is...
overly covered by other topics, other modules on this course, however, for the completeness of discussion, I want to make sure that we covered everything that is relevant for development of our stability model.
So, the next thing that I'm going to talk about will be transformers.
Now, transformers are extensively covered in the units previously when you talked about the modelling.
What I want to recapitulate here only is to mention two things, whether we are talking about generator step-up transformers, unit transformers or auxiliary services, transmission, transformers or distribution transformers.
There are many, many transformers in the system.
Their restore capacity's about five times of the total MVA rating of the generators.
So, there are practically more transformers in the system than generators.
The good thing about transformers from our powers and dynamics point of view is they do not have any movable parts.
As they don't have any movable parts, they do not contribute in any shape or form to electromechanical stability in the sense of contributing to movement.
The transformers that are relevant for us are only few types.
One is classical transformer which is simply represent as reactance or eventually as an impedance reactance plus resistance.
The other group of transformers are tap changing transformers.
Now, tap changing transformers particular interest to us are those that can perform their actions automatically and under full load.
Because tap changing transformer means that you can change the turns ratio between the primary and secondary winding self for the same primary voltage that you can get different secondary voltage that is in vice versa.
Now, if you do that off load, you have to disconnect transformer, change a tap and then reconnect it again.
Now, this certainly cannot contribute to system dynamics in any way of much more greater interest...
Much great interest are obviously those transformers where we can do that without de-loading them, without off-loading them.
So, when they can perform this switch from one turns ratio to the other automatically.
That change can be in a range typically between 10%, 15%, and usually up to 32 steps are involved moving from the minimum to maximum output at the secondary side compared the primary side, with the steps ranging between 1 and 1.5, sometimes 00.5 per unit voltage.
So, there's a reasonably fine regulation voltage at the secondary side by these tap changers.
This change can happen very, very fast.
With more transformers moving from one transmission to the other, it's very fast, in less than a second.
However, in practise, this doesn't happen that fast.
So, they are capable of doing tap changing very fast but in practical situations, this takes tens of seconds, why? Because, typically, the protection is setup in such a way that we want to make absolutely sure that the voltage is lower or higher and then based on that continuous information for a certain number of seconds, we make a decision of changing a tap.
That's why their action is not as fast as it can be, it's slowed down by protection settings.
Now, the two types of regulating transformers that we're interested in, one is if you like more conventional one, that we refer to as on load tap changers or sometimes OLTC or ULTC depending on the preference of language use.
It's either on load tap change or under load tap change, that's why there is difference, OLTC and ULTC, or simply LTC which is low tap change transformers.
The other group of transformers is phase shifting transformers where we do the same thing.
We kind of change a tap but we are not changing the voltage magnitude instead, we are changing the phase angle between primary and secondary voltage.
Now, when you think about this, classical...OLTC, on load tap changing transformer, changes the magnitude of the voltage.
By changing the magnitude of the voltage, we regulate the flow, as I said before, because of the coupling between magnitude and reactive power.
By changing the magnitude of the voltage, we change the flow of reactive power.
On the other hand, the phase shifting transformers or quadrature boosters as they are commonly known, they do not change the magnitude, they change the phase angle instead.
So, by changing the phase angle, they control flow of real power.
So, depending whether we need to boost the voltage or reroute the power through the system, we can apply either conventional on load tap change transformers or quadrature boosters.
Now, this is a function that is now considered as something that type of FACTS devices can provide.
So, we have static transformers or static tap change transformers which can do the same thing as either on load tap changing transformer or phase shifter by using power electronic.
So, there are actually this much, much faster.
But the role of both of these transformers, whether they are changing angle or magnitude of voltage is to affect power flows of the system.
Now, they cannot react fast enough to contribute to system angular stability, but they are essential for voltage stability.
So, all the studies or maybe not all but vast majority of studies involving voltage stability has to consider as an essential component the operation and coordinated, more importantly, coordinated in operation, coordinated tuning of on load tap change transformers.
Because if they are not properly tuned and sometimes even blocked, prevented from operation, they may start tapping up or down in undesirable direction.
They may actually precipitate voltage problems rather than prevent them.
From the point of view of angular stability, because they are not fast enough, they cannot build much.
But, because it's our dimension based on the principle of the operation, new breed of FACTS devices is built which operates in the same way, except they are static switches.
They are shown in studies, obviously, to be very useful for system angular stability.
In terms of dynamic modelling of these transformers, it's a very simple first order differential equation shown at the bottom of the slide which only has set voltage, desired voltage at the end, so, we...
Not is the voltage that we had before disturbance, 'K' is the voltage to be controlled and then there is a time constant which is typically 20 to 60 seconds.
Even though, practical change from one tap to the other can be achieved in a few milliseconds because of the protection setting, this is not achieved that fast.
Now, when we are talking about transformers, the other very important thing about them is they're depending on the winding connection.
They may alter the current flows through the system.
So, in case of winding connections which involve the earth.
So, grounded start, for example or delta or ungrounded start, they may act as a switch, or connection in zero sequence network.
So, why am I talking about zero-sequence networks when I said we do not use this type of models in power system stability study? Well, most of the faults in the system are not three phase faults, they are rather single phase faults or other asymmetrical faults.
In case of these faults, in order to appreciate the effect of the fault, we have to calculate actual power flows through the system under such circumstances.
So, under such circumstances, we need to model different parts of the network appropriately, including zero sequence network of the system.
So, equivalent zero sequence network.
So, zero sequence network, the topology of zero sequence network of the system will be vastly different depending on the type of transformer connections.
Hence, it is absolute necessary to be aware of different zero sequence equivalent networks of transformers and use the appropriate network for modelling propagation of zero sequence currents in case of asymmetrical forms in the system.
And, that's all that you need to know at this stage about modelling of transformers for dynamic studies.
The next block will be about...
The next section, I said, not block, will be about modelling of transmission lines and we'll do that in a moment.
 
Modelling of Transmission Lines, automated transcript 018-10-12 ---  
LECTURER: 
Talking about transmission lines, similarly as with transformers, transmission lines are very simplistically modelled in parts and dynamics studies again from the very same reason they do not involve any movable parts, there is no contribution in terms of changing the speed of the rotors or generators and for that reason we typically model them as a very, very simple- very simple, impedance, resistance plus reactance in series.
There are few things to mention here briefly just for the- for the completeness of discussion is that the effect of lines, how the lines are modelled, to preserve accurately their effect in the system, depends a lot on the length.
And though these length of lines is not that critical for a modelling system dynamics, the way how they affect the system depends a lot on their length.
That's why I want to spend a few minutes talking about that.
Typical classification of lines is in 3 groups, short, medium, and long, and these lengths there are different limits provided by different authors.
But in order to simplify this you can say, short, would be lines shorter than 100 km, medium would be those between 100 and 300, and long would be above 300.
The reason I want to talk about them is not that much about how do we model them, but about the effect they have on the system operation.
Short lines.
Are typically modelled by a very simple model which is a pi equivalent.
Pi equivalent of the line which involves only impedance, series impedance and to susceptances at the start and the end of the line half of each end of the line.
So, it's a very, very simple model.
Quite often this model is built in- not quite often, practically always is built in commercial package so we don't have to worry about it.
And this is the model which is suitable for both- for short and medium lines.
In case of long lines, the model is exactly the same except that the parameters are calculated differently.
So, this is distributed parameter model when we take into account the length of the line and infinitely small, and very, very small change in parameters as we are moving across the length of the line.
These models are appropriate for modelling very long lines, very few systems actually in the world have lines in excess of 300 kilometres.
These are sometimes, these types of lines could be found in countries like, United States, Canada, Russia, China maybe India.
So, you know, very big countries.
And maybe some of the countries in the North of Europe, like Sweden, Norway, and in Finland, because they are rather long and thin countries.
But most of the time the lines are not that long.
So, use of distributed line parameters is important for harmonic studies for example, or for studies of electro-magnetic, not that much but wave propagation, in particular because studies of wave propagation, for example, lightning strikes.
This is what happens in lines and as I said, primary side of transformers.
So, for this type of study is absolutely essential to model lines using very detailed models.
For stability studies, we quite happily can live with the model that is conventionally used for short and medium lines which is a very simple pi equivalent network with resistance and reactance in series branch of the model and 0.5 of the susceptance at each line of the model.
But as I said before, the point of me talking about the lines at all, is the point I want to make about the effect of these lines on overall system operation.
So, we can- you may have people talking about the..
the lines have been required to operate flows to their thermal capacity.
So, if you take a short line, if you start increasing the power transferred through that line, we can go as far as the current is so high that line, not really begins to melt, but it starts to sag too much.
And this is the limit- this is a physical limit beyond which we cannot push more power through that line, more current because current power is about the same.
So, we cannot push more current at that line.
And this is the limit- this is the thermal capability limit.
That limit is the only limit that we have to worry about' in case of short lines.
Once we start moving to longer lines, lines which are, as I said, about...
between 100 and 300 kilometres roughly or 80 to 50 depending on different classification, but that's the general range.
So, once we talk about the range of about the lines between 100 and 300 kilometres.
What happens there? When we start increasing the power transfer through these lines and increasing the current, before we reach the point when the lines start to sag too much because of the high current, voltage and the end of the receiving end of the line drops below 10% of the statutory limit.
So, we have a voltage regulation problem.
So, we have to stop pushing power through the line, in order to maintain the voltage, at the end- at the receiving end.
So, how we do that? We in that case connect shunt capacitor for example, at the end of the line to boost the voltage, to restore the voltage of receiving end, and then continue to push more power.
And then the limit again becomes physical property of the conductor.
So, once we reach that limit, before- after which the line will start to sag, we have to stop.
In case of long lines, lines in excessive 100 kilometres, so what happens? We start pushing the current through the line.
So, the first thing that happens actually is not the voltage problem, is not the thermal problem, is the angular problem.
So, the angle between sending and receiving end of the line becomes very large.
If the angle is very large, so from the stability point of view, we are approaching stability boundary.
So, from the stability point of view we have to stop pushing more current to that line.
So, to solve the problem, we then connect series capacitor for example.
That capacitor will reduce the impedance of the line and we can continue to push more power to that line.
Now, by continuing doing that, we will then encounter voltage problems.
So now we connect shunt capacitor at the end of the line to stop the voltage from dropping further and then we continue to lower the line further, again the limit is ultimately the thermal capability of the line.
So, this is how these three types of lines actually lines affect operation of power systems and ability of the system to transfer power between two buses.
Now, people have obviously realised that many, many years ago, and that's why we have devices like shunt and series capacitors and tap changing transformers and quadtree boosters because both or all four of them or four of these devices are actually there to do something with power transfer, either to regulate voltage or to enhance power transfer.
Shunt capacitors practically boost the voltage same as low-type changes, they regulate the voltage, manage it.
Phase shifting transformers, are quadtree boosters and serious capacitors effectively change the length of the line.
So, they open the line, or shorten it to transfer more power.
Now, having these basic principals in mind, this makes a nice introduction to new breed of devices to do the same job as tapped changing transformers, quadtree boosters, shunt and series capacitors do, which are facts devices.
So, facts devices do exactly this role they are controlling voltage and power transfer or in other words, real and reactive power flow through the line, but using power electronic base devices.
So, they are much faster and they enable continuous smooth regulation of real, reactive power and voltage.
And this is how they came into being.
Facts devices, there will be a set of slides I believe somewhere later, which show typical types and installation and so on and so forth and we are going to spend time on that I just want to introduce them now by saying that their role is to regulate voltages and real and reactive power.
And because they can do that very fast, much faster than any of the device that I discussed before, because they are based on power electronics.
Additional controllers are, recommended to be applied and in some cases have been applied in some of these devices to enhance system angular stability because they can by modulating either power transfer or voltage within a time frame of few seconds or after up to seconds they can influence then angular stability.
That's why they are important for system stability.
 
Modelling of PS Loads, automated transcript 018-10-12 ---  
LECTURER: 
The final component that I want to talk about today will be power system loads.
We talked about...
we talked about generation, we talked about transmission system components, lines and transformers, and in order to complete the circle of power generation transmission and distribution, we obviously have to talk about the end.
The end is the load.
What is at the end, it's the load.
So, we had the generators, generators that mostly we are talking about synchronous generators here.
We do, of course, acknowledge the fact that there are more and more non-synchronous generators in the system and I mentioned that the presence of the non-synchronous generators as well as non-conventional loads, affect the way how system responds to disturbances affects the system dynamics.
But still the dominant presence in the systems are synchronous generators.
So synchronous generators are the major source of electrochemical dynamics, if I can say that in that way.
They have to be controlled and they can be controlled by excitation systems which involve the exciter itself, which is the source that produces AC current and injectors in the rotor and associated regulator so the exciter and regulator together form automatic voltage regulator and then there are also part and stabilisers attached to it which control the speed.
Then we have turbines and governors.
Turbines that are prime movers so they convert a form of energy and different working fluid into electrical...
into mechanical power, mechanical torque, which then rotates the rotor of the generator so whether these are steam, nuclear gas, wind, hydro, whatever the turbine is, then they have a regulator which controls the speed of the movement of that shaft which attached to the rotor and then control the speed of the rotor itself and influences the generation of electrical power.
So, this is the generating bit with its associated controls which is turbine and governor and exciter and...or AVR and PSS.
That power once generating obviously has to be transferred from the point of generation to the point of end use through transmission lines and that transmission is either through overhead lines or underground cables and transmission is facilitated by having transformers, if you like over and there for us to increase the voltage and reduce the losses over transmission then reduce the voltage so that we can supply whatever load is at the end.
So there are transformers that do this essential things rising the voltage, decrease the voltage...
and additionally these transformers and some other devices like five devices around it can help...
regulate the amount and the fashion in which the power is transferred from one and to the other.
And then we come to loads.
Now, loads have been for many years, underrepresented in system, stability studies because they are not contributing, people thought, as much as do generators to system stability now that obviously has been changed, this outlook has been changed and many people have been working on load modelling.
A lot of reports have been written, a lot of practical examples, have demonstrated how power system loads affect very significantly voltage stability in particular, and to substantial effect, extend the angles, which is well, many of the voltage collapse...
currencies in the world and blackouts which are not necessarily voltage collapse that have occurred in the past 15, 20, 30 years have been caused by not understanding the rule of loads and to what extent they can influence the system dynamic behaviour.
The loads, one of the reasons why they have not been modelled very accurately is they are notorious tendency to change because the load at the end is a compilation or combination of various devices of different size, different nature, different model of operation and quite often completely under the will of the end users so where they want to connect or disconnect them excluding obviously large industrial plants which have a scheduled operation.
Now because the composition of the load, we are talking about system stability.
System stability deals with transmission system typically of the voltage levels above 100kv.
Now there aren't actually loads connected at that level apart from very few, very high industrial loads and most of the loads are connected at lower voltage level.
So, and the time or the point of interest which is 110 and higher voltage level have a combination of many, many, many different loads, diverse loads which may or may not be all present at the same time so there are composition changes and naturally, the way how they respond (INAUDIBLE) change as well.
So, what we are interested in is how these loads depend on variation involve through frequency but because of the share number of different devices and the combination which changes in time and in space because of different location, the system different combination exists, it is not very straight forward to this modelling.
The most widely used models traditionally are very simple, classical, static exponential load models which represent only real and reactive power dependants on voltage through a very simple exponential function where coefficients and P and Q, referring to voltage, real and reactive power coefficient typically are set to either zero, one or two.
This is because of the nature of the logic you can find in the system either they are totally constant power norm dependent on voltage, say like induction motors, or constant currents say for example fluorescent lights or lighting industrial plants or constant impedance load so loads which are heaters, boilers, or similar which where voltage depends, power depends on voltage with the coefficient two.
Obviously, these are most widely used models, very large number of industries even today use these models.
Even in dynamics, that is even they do understand and they do realise that a very large proportion, about 70% of full generated power is used by warm type or the other of electrical motors, whether these are induction or not but the very large percentage of power, produced power is used by induction motors.
Induction motors certainly are not starting devices.
In spite of that, a vast majority of studies are even today carried out using these very simple static exponential load models and typically where with real power model as a constant impedance with exponent zero and reactive power as constant sorry - with real power model as constant power with exponent zero and reactive power model as constant impedance with exponent two.
Even though that is the case, people have realised based on long term dedicated measurements and load model and projects are all around the world.
These coefficients and P and Q actually can vary in wide ranges so most widely reported ranges are for real power of voltage exponent because zero and three and for reactive power between zero and seven though there are individual components of loads where this reactive power voltage coefficient can be much higher that it can be about 11 or sometimes slightly higher.
Now, understanding the fact that load composition changes, moving from conventional classical load model, the next combination, the next option was to put all this together.
Constant power, constant pin, constant load model and form polynomial model often referred to as zip model because it's constantly in pin z, in constant current I and constant power P.
So, this ZIP model is probably the next most frequently used model in load modelling when static load models are used.
Now, because the system frequency changes much less than voltage in the vast majority of systems in particularly in systems we're trying to connect and dominate by large steam generators.
Dependency of load and frequency is much lower.
So, in most studies involving...
in most stability studies involving load frequency dependency is neglected.
Though it is obviously understood and realised that there is a load dependency frequency.
So, if that unpins the dependencies to be included it's usually done by adding a factor multiplier which demonstrates how the load varies in frequency and then there is an appropriate frequency dependency coefficient which can be positive or negative depending on whether you're talking about real or reactive powers.
So, real power is typically positive because it's three and for reactive it's negative between typically minus two and zero.
Now, as I said before that's all fine and then when we put all these models together we can come up with a very comprehensive load model.
Now, the ones that is the most comprehensive model is at the bottom.
It's the model that's representing a combination of constant pins, constant power and constant current model plus some other dependence of voltage...
Sorry, on power and voltage plus dependency on frequency.
Now, this is a very complex model, but however complex it may be this is still a static model.
So, following the change in voltage for example step down in voltage there will be a step down in real and reactive power.
It doesn't really matter how many components we have in these expressions to that right.
These components only define how much real and reactive power will drop following the voltage drop and it will stay that level.
As I said, people do understand that the vast majority of power is consumed by induction models and other types of models.
So, the response of these models certainly is not static.
So, following the initial disturbance the power may drop and then the recovery will start.
That recovery may be either exponential or auxiliary.
Depending on the type of dynamics involved whether these are induction models or tapping of tap changing transformers which happens automatically and if you're interested in longer term.
Then the voltage recovery can last from a fraction of a second... sorry, power of recovery following a voltage disturbance can last from a second to several minutes.
And here are the recorded responses of real and reactive powers in real power systems in two different countries.
One is showing very fast recovery of both real and reactive power on the left with the time frame of a fraction of a second.
The other shows the recovery of again pre unit of real power recovery is the function of time.
Shape is the same as the shape of the real reactive power recovery on the left hand side, the bottom slide or even a real power recovery in the middle of the left hand side figure However, the time axis there.
The horizontal axis, if you look on the right, is in minutes.
So, we are talking about voltage recovery or power recovery following the voltage disturbance.
The last thing of the order of 15 minutes.
While on the left hand side we have a recovery which lasts about 0.2 seconds.
So, depending on the type of the load, of the mix of the load or depending on the types of devices involved we may have different recovery.
Now, I always say in spite of the fact people do understand that loads respond dynamically there is still a vast number of studies which are carried out using constant power load model and constant real power and constant reactive power model for both static and dynamic studies.
These are the results of the (INAUDIBLE) which were completed very recently which shows constant power model is by far the most dominant type of load model used in this study and even that load is the most widely used even in majority of power stability studies with constant for real and constant pins for reactive power.
The key question for load model which attracts a lot of attention nowadays is how accurate it needs to be? There are more loads in the system than generators.
So, if you start going around and modelling every load accurately we know how to do that.
It's not a problem.
It does require effort, monitoring and then some analytical computational skills in fitting... its basic load model is a curved fitting problem where you find the structure of the model.
You've got your responses and you try to fit the right perimeters to this model.
So, this is not an issue.
The issue is you have to have enough monitoring equipment and time and personnel to send around the system to do load modelling.
The question is: do all loads need to be modelled? And then if some of them do need to be modelled how accurate should they be done? So, these are the questions that most of the people working currently in the area of past and load modelling are trying to answer.
To simply limit... to reduce unnecessary waste of time.
So, we can focus the effort on only load models that need to be only two buses, where the loads need to be modelled and we can focus that effort to develop only the models of certain accuracy because if the 10% variation in the accuracy of load models affects the system stability studies depending on what stability study you are doing only by variation results of 0.1% then obviously there is no need to go into much better accuracy of load model.
On the other hand if 10% accuracy of load model results in 20% accuracy of the results stability study clearly that load model has to be developed much more accurately than 10%.
Parameters have to be much higher accuracy than 10%.
So, this is the way that people are looking at it at this moment trying to develop appropriate models for these types of studies.
This is the end of the block on power system modelling.
So, this is the second block or this was the second block following the block which was the introduction to passing dynamics.
So, now we are equipped to start talking about performing system stability studies.
So, after having defined the types of dynamics that you can see in the system and why it is happening and what affects it and after discussing different components that participate in generation to transmission and use of electricity and the appropriate models of those components and devices for system stability studies and developing their models.
Now, we can put all this together and start addressing the issue of power stability studies.
The first block that we are going to address next will be a small disturbance stability study.
I'm going to talk about both the required modelling and physical behaviours of the system under small disturbances and talk about which models are applicable for either small or large system studies.
Then we are going to move onto transistor (INAUDIBLE) studies, studies involving large disturbances and then we will conclude with a block or a chapter on methods of enhancing power system stability.
 
Basic Concepts, automated transcript 018-10-12 ---  
LECTURER: 
Hello again, here I am and hope you are there as well.
So today in this set of discussions we'll continue where we stopped in previous two blocks.
The first block as you remember was about general introduction to powers and dynamics which was followed by discussing how different components of power system from generation, transmission and load are model to facilitate power system stability studies.
In this block of lectures we'll continue with discussing first small disturbance stability and methods of doing that and then large or transient stability.
That will be followed by the final block will be enhancement of power system stability which will follow after I finish with these first two.
So the next session is about small disturbance stability.
So the best way to approach the problem of small disturbance stability is to start with a very simple system.
One machine infinite bus system because that system can be used to physically explain what's actually happening while we're discussing small disturbance stability.
There are few things that we can assume first which is that nothing affects the voltage magnitude so we assume that voltage magnitude is a fixed and that the phase or frequency are also fixed and not affected by external influences.
Now simplified representation of a network with many generators connected by lots of lines with small impedances and where the capacity of the independent generator is very small compared to the capacity to the rest of the system is something that we are talking about here.
Why? Because that enables us to see how the variations in external disturbances may affect behaviour of a single machine.
In many practical systems, even in practical case studies, even realistic systems this is a model that's used because by setting up the small disturbance of individual machine then ensuring that all individual machines are stable, the whole system generally is stable except in some very very rare situations where there are control interactions and interactions between different machines.
So we will start by looking into electrical power and rotor angle characteristic again to makes sure that we understand fully what's going on there.
Now when deriving the model for electromechanical behaviour of individual machines we discussed before that there are components which affects its damping and synchronising torque.
The first thing that I'm going to talk about here is this damping torque.
If you remember there was a damping component which is proportional to speed in synchronising component of this proportional to angle of variation.
Now by focusing on the damping component alone which as I said before is predominantly influenced by the action of damper windings on field on the rotor.
This damping component consists basically of two elements.
If you look the equation in front of you at the top of the slide which is a component coming from a d-axis direction and the component coming from the q axis direction.
And if you look how this is damping power or damping coefficient varies with the operating angle.
You can see that the maximum of damping power appears when the angle...the rotor angle is about 90 degrees and the minimum is when the rotor angle is very small or zero.
The fact that the maximum damping is appearing as a contribution of the d-axis and minimum as a contribution to q axis is of less importance in the moment.
The more important thing is that the operating angle when the maximum damping is inherently present in generator is at 90 degrees.
Now the other component to look here is where this damping power appears.
The top...at the top of the slide is the electromechanical equation and if you are going to refer many many times as I wholly mentioned yesterday that change in speed is proportional to differences between mechanical and electrical power.
Obviously electrical power has now this damping component included there.
So the thing to look at is the damping component, the damping power PD id proportional to change of speed as I would said in the slide when I was discussing how change in electromagnetic torque has two components, synchronising component and damping component.
damping component of the synchronising torque is effectively the same as damping power that we're discussing here.
So by looking electromechanical equation we can see that damping power actually adds to electrical power and balances mechanical power coming from the turbine.
So in order to make sure that the acceleration is small or non existence PE+PD should be equal to PM.
So as long as PD is positive then it adds up with PE and balances PM.
If PD is negative then it actually has a detrimental effect because it reduces the value of electrical power.
And therefore the difference between mechanical power and electrical power becomes bigger.
So it is in our interest, you know how to stabilise a machine or reduce the acceleration during the disturbance is...
the interest is that PD is positive.
Now looking at PD alone, PD has a...some damping coefficient KD which is proportional with the change in speed.
For this component for PD to be positive it's clear the KD and delta omega have to have or have to be of the same sign.
So if delta omega is negative KD should be negative.
So negative times negative gives a positive value.
If delta omega is positive then KD should be positive.
So the coefficient KD, the damping coefficient therefore has to be in phase with speed deviation.
If it is in phase with speed deviation then damping power is positive and then it adds up to or with electrical power and helps balancing mechanical power.
At this point we can jump few steps ahead and say that DC is the main requirement of power system stabiliser which is added to extension system to stabilise the generator following the disturbance the main role of power system stabiliser is actually to inject this KD this signal which is in phase with the speed deviation.
So the role of PSS is to produce a damping signal which is in phase with the speed variation.
So going from there further the other component we discussed yesterday when we talked about the variation electrical torque is there is a synchronising torque.
Now synchronising torque has a synchronising torque coefficient or synchronising power coefficient which is proportional for...
with variation or to variation in angle.
Now that synchronising power coefficient is derived as a first derivative of electrical power.
And if you look at the expression which is the second line on the slide.
Synchronising torque coefficient is E*V over X cos...sine delta.
When we plot it we have a line on the right hand of the slide which is a dashed red line.
And by looking at it you can see that synchronising torque is maximum, is at its maximum when the angle is zero and its minimum when the power angle is 90 degrees.
So when the machine is a lightly loaded and operates at a very very small power angle the ability of generator to pull itself back together or to pull the rotor back to previously operating condition per to disturbance is the largest.
As the machine becomes more and more loaded synchronising torque ability to pull the generator rotor back reduces.
So if you remember the discussion in the beginning of these lectures when I said that we can compare the synchronising torque with the stiffness of the spring.
This synchronising torque in this expression we see here actually tells us that as the angle is smaller machine is lightly or lighter loaded, then the stiffness of that spring is larger.
As the angle becomes bigger the machine is more loaded the stiffness of the spring reduces.
Interesting thing to notice also is that synchronising torque coefficient is at its minimum when the angle is small while damping was, sorry synchronisation, its maximum angle is small and the damping was the minimal when the damping when the angle is small.
As the power angle increases and becomes very very high synchronising torque reduces and damping increases.
So these two components which contribute to variation in electrical torque are acting in a way in opposite direction when one is large the other is small and when the other hand the first one was small the other one is large.
So obviously the optimum operation for a generator is somewhere in between when you get best of both worlds and if you look how the oscillations look like a machine oscillation rotor oscillation is forming a disturbance as we move along the horizontal axis in p delta curve, power angle curve.
You can see that it's very small angles when the machine is lightly loaded we have a lot of oscillation which are not...
not properly damped.
A lot of oscillations means that the synchronising torque is...is large.
So we have a higher frequency and many oscillations it will become damp because damping is poor at lower loadings at lower voltage angles, these oscillations last for a long time.
On the other hand if you look operation at a high angle at a very large rotor angle too closer to stability boundary close to 90 degrees.
We can see the damping is very good, so the angle goes down...down very quickly and there are practically no oscillations.
So synchronising torque at that point is not very good.
So comparing these two operating points but you can see that obviously the best operation would be achieved, if the machine operates in the power angle of about 45 degrees or somewhere in the middle because in that case we have some oscillations and we have still reasonably good damping and it is...is the main reason why machines are designed and operate in such a way that their steady-state operating point is at the angle of about 45 degrees.
The other thing that they can mention here is that sometimes machines are required to operate in leading with leading power with leading power factor which means they are actually not producing reactive power but they are consuming reactive power.
This is in situations when we have a lot of reactive power in the system and we have to consume some reactive power basically to...
to reduce voltages because in this case is during the nights typically that they do too much reactive power and results in too high voltage, so machines have to be converted into practically reactors that will consume reactive power.
In that case, typical operation results in rotor angles which are closer to stability and they become higher than machines then operate the power angles about 60-70 degrees.
So when you look at the power angle curve, if we are closer to 90 degrees, the oscillations will be better damped but the ability of machine to pull itself together synchronising torque reduces that's why...
that's why the operators of the machines the power plant owners are not very happy if the generators have to operate in with leading power factor because in that case ability of generator to remain stable following a disturbance reduces and synchronising torque...torque drops.
So these are examples on several next several slides examples of leading versus legging operation of power factor operation of synchronous generators.
So with lagging power factor we have typically angles of about 45 degrees or thereabouts or even less and with leading power factor the initial angle is much higher.
One thing to mention here also is the effect of AVR.
When we had AVR, so what it does? It basically immediately after disturbance notices the voltage drop and it boosts the voltage.
So this boosting of the voltage following disturbance results in temporary shift of the maximum angle to the right.
So the angle that the stability boundary which is 90 degrees in steady state is not anymore 90 degrees during disturbance.
It is 90 degrees on new characteristic which is shown here in dash line which is results of AVR action but compared to steady state operation, these new 90 degrees on the new sine wave curve have sine curve is actually shifted further to the right.
That's why during the initial disturbance machines with AVRs with...with properly tuned AVR can withstand shift of the power angle beyond 90 degrees and then survive the initial disturbance.
Now in order for that to happen is the generators that the AVR are tuned in such a way, so that the maximum boost of excitation voltage is achieved within first about half a second since first half a second basically corresponds the fact when the peak of the first swing is achieved then the generator achieves a maximum rotor angle, the power should be, the electrical power that balances mechanical power during disturbance should be increased to the maximum within this first quarter of a cycle of the electromechanical swing.
So to make sure that the generator rotor doesn't escape and during that period we have this shift of power angle further to the right, so that initially it looks like as if we are operating with angle which is more than 90 degrees which is obviously not the case because we are not talking here about steady state here talking about transient operation only.
Now the problem with AVR which acts by that is that in many cases when the system is highly loaded and when we have a large...
large load and long lines, the fact of the of this fast boost of the voltage and tuning of the AVR and parameters of AVR leads to situations when actually the damping produced with the AVR may be actually negative.
So without AVR we may not have properly damped oscillations or system and not be able to withstand initial disturbance.
Once we add AVR, there is a voltage boosting so initial acceleration of the generators rotor is arrested.
However, the resulting damping torque is becoming reduced or even negative.
So this negative torque which is a consequence of application of AVR may lead to increased oscillations following the successful arrest of the first swing and that's why application of fast acting low time constants AVR brought this to attention of people who are tuning controllers and this is where the need for introducing additional controller pair which is power system stabiliser which then is applied to reduce the oscillations which appear in system response following the successful arrest the first acceleration.
So even though AVR obviously, helps a lot with initial control of the acceleration of the rotor, subsequent oscillations may become negatively damped and increasing therefore, we need another controller to reduce and control them.
Now this effect is most...more pronounced the fact of say negative interference between AVR and PSS is more pronounced as the AVRs are becoming faster.
So with more than digital AVRs with short time constant high gain the effect of potential or detrimental contribution of AVR to damping of oscillations from this tethers becomes more pronounced.
 
Modelling Requirements, automated transcript 018-10-12 ---  
LECTURER: 
In order to study the behaviour of the machine when exposed to small disturbances, we need some mathematical apparatus for that.
One thing to remember first for the whole model, the whole system model consists of a combination of linearized equations.
Small disturbances around the operating point and these linearized equations involve differential equation and algebraic equation.
Now that can all be represented in a form of a combined differential algebraic set of equations which is presented here in the standard system state flow.
Now linearization means that we have different components which are originally non-linear and then by applying first derivative to different matrices in the model, we get linearized components which are applicable only for one operating point.
Important thing to remember here is that small disturbances is that the conclusions made about small disturbance stability are applicable strictly only to a point that we are talking about for one operating point.
If you move from one operating point to the other, then we have to repeat the linearization process to introduce new initial values and to check the small disturbance stability again.
So if you want to design or to make a robust conclusion about small disturbance stability, you have to repeat for a large number of operating point along the line of all operating points or path a system may follow during the operation.
So the model itself has several components.
Obviously, there is a state vector or state variables which involves all components of the model which appear as a part of derivatives in differential equation.
So differential equation if you remember, we had in the original model, there was a derivative of angle, derivative of speed and derivative of some fluxes or voltages in the model that is commercially used in power system analysis software.
So there are between two and six equations per synchronous machine.
Now if you model loads as dynamic components and if you model controllers as dynamic components, then the number of these state variable increases.
If we assume initially that the system doesn't have any control, it only generate to its present and if we say this generator is represented by the classical two-order model.
This is the model which has only Swing equation then state, vector of state variables will have two components.
One would be speed and the other the angle.
In addition to that, we have vector of system inputs and then obviously we have a set of equations which connect inputs and outputs.
Finally, we have the outputs of the model.
Now the output Y in this case consists of values that we are calculating at the end which may be voltages, may be current, may be power, whatever we decide to look at the final out.
So the overall model then starts from identifying initial operating point by equating with zero, we can then find out how the overall model looks like following the linearization.
This is example which shows how the linearization process from the left hand side have non-linear.
First all the differential equations and algebraic equations.
After linearization, becomes actually a set of fully linearized differential and algebraic equations.
Linearization once again means that we do derivatives of all matrices A, B, C and D that are present in the model.
Now this is the process which nowadays is performed by only practical on its own but in many commercial packages.
So we are not doing it anymore manually.
It's done for us within MATLAB, within say, DIgSILENT, within PSSC and many other commercial software packages used for this purpose.
 
Mathematical Tools for the Analysis, automated transcript 018-10-12 ---  
LECTURER: 
So once we have, once we have the model, once we have the states, state based model of the system, which consists of system state matrix, matrix of input and output variables.
We need to define some, values that are helpful and then find system stability.
And this is where the problem of parson dynamics, in general appears, and general perception that parsons dynamics is difficult subject, because it deals with a lot of mathematics.
So this mathematical bit is just right here, when we are applying some linear algebra, and some control theory techniques to discuss the systems stability.
So the first thing that we have to find is the eigen values.
So eigen values are calculated from the system state matrix, using this, known equation, obviously you've seen that before, in mathematics and in control system theory.
So by finding determinant of the matrix in the brackets in this third equation on the screen, we can calculate system eigenvalues.
Now, eigenvalues is one useful quantity calculate in addition to them, we need to calculate left and right eigenvectors, using the equations at the top of the left hand side corner, of the slide.
And then these eigenvectors are normalised so that their product is one.
This is the way how we just condition from (INAUDIBLE) will come again back to this while we are actually doing it.
So, the key question is, why do we bother to calculate eigenvectors and eigenvalues? Why do we need them? When after all, the only thing if you want to find out is, whether the machine is going to be stable or unstable, following a small disturbance.
Now, once again, stable means that following initial disturbance, the rock too will start to oscillate.
And it will oscillates for some time, say five, six, seven seconds, and eventually the oscillations will disappear, and machine will return to initial operating condition.
Once again, I want to make this distinction, for small disturbance stability we always return to initial operating point.
For a large disturbance stability if the system is stable, we may return to initial operating condition but, we may also move to another stable operating point.
But we are talking about small disturbance stability, now so that, after the disturbance, we always return to initial operating point.
So, once again, we want to find out, whether the following disturbance the system will start to oscillate, and return to stay the state of operating point.
If that is our interest, why then we bother to calculate, eigenvalues and eigenvectors and to produce all these matrices and all this highly complex mathematical tools, when the answer, when the question is simple.
Will this oscillate and will this oscillations disappear.
So the answer to that question is, given the first equation on the screen.
As you can see, this is, mathematical expression of time, dependence or variation of system state variable.
So any of the state variables, and once again, state variables, system variables are, machine parameters or, or system parameters which appear as differential equations, in the model.
So one of these xi's can be angle, or speed of the rotor, or transient voltage, or sub transient voltage, etc, etc, etc.
So let's focus on the angle.
Because typically we look the angle responses versus time.
So if we assume that this xi is an angle, the equation actually shows how this angle varies with time.
By looking at the equation, we can see it has n components, and n is the number of eigenvalues.
Now if the state matrix a, which we defined previously, is of the size, it's of the square matrix, is if it is of the size n*n or n by n, there will be n eigenvalues.
So this equation has n components, which means eigenvalues lambda one, lambda two and so on.
Until lambda are all involved, in describing the time evolution of the variable, following a disturbance.
What can you also see in this equation, is the addition to involvement of all eigenvalues.
We have left and right eigenvectors, v and w.
So all eigenvalues, and all eigenvectors, are involved in describing the oscillation following a disturbance.
In addition to them, we obviously have initial value.
Delta x of not, this is the initial value of the variable, so which describes where are we starting from? So when you look this mathematical expression, this explains that, eigenvalues and eigenvectors we calculated previously, are all involved in describing how the system actually will oscillate.
How individual variables will oscillate following a disturbance.
So if you look, the eigenvalues first, they have real and imagined part sigma and omega, and depending on these values, and if you look at this slide here, which is not exactly next but few slides forward, which discusses about eigenvalues and stability, there is all the formula at the bottom which says, that the exponent of e to the lambda t, where lambda is a complex number, has two component one which is e to the sigma t, and the other which is e to the j, omega t.
So e to the sigma t is a magnitude, and e to j omega t, is the actually frequency of oscillation.
So if you go back now, here, and look this equation.
So if lambda is real number, if the eigenvalue is a real number, then e to sigma t will not be oscillatory.
It will be constantly exponentially increasing.
If lambda is positive, then as the time goes by, each of the sigma t will constantly increase.
So for these oscillations to be, stable, not to increase, all lambdas have to be negative.
Because with the passage of time, each of the component will disappear.
If the single lambda is positive, then with the passage of time, that particular component will continue to grow, without any oscillations under the assumption that lambda is a real number.
If lambda is a complex number, then each of the lambda t, will be a magnitude times a certain oscillation.
Again, if the real part of that complex number is positive, then e to the sigma t will be increasing oscillation, with the frequency omega, where omega is imaginary part of eigenvalue.
If real part of the eigenvalue is negative, then each of the sigma t will be decaying with time, at again the same frequency, which is omega, which is again, imaginary part of the, of the eigenvalue.
So, the shape, if you like, of the eigenvalue, whether it's real, or imaginary number, will determine how the overall response will look like.
But it's not the shape of one eigenvalue, but the shape of all other all n eigenvalues, because they all participate in forming the overall system response.
And on the next slide, you can see that, depending on the combination of different eigenvalues, we may have responses which are dump, undumped, exponentially increasing or exponentially decaying.
in order for the response to be stable, all eigenvalues would need to have real parts which are negative, or if they are real numbers, they have to be negative.
If there is a single eigenvalue who's real part is positive, or if the eigenvalue is a real number and positive then that particular component of the equation, the top will continue to grow while all the other, while all other will disappear.
So, if you look at this small example here, this example where we have the system response composed of three components, only three eigenvalues and the selective values are given above.
So, when we look each of the modes individually, we can see these are oscillations with different decaying rate, and different frequencies when they are put together at the bottom right hand side corner, we have a combination of these three modes and then we have overall system response.
So these electromechanical individual, or this eigenvalues are often referred to as a system modes.
And they in a way represent harmonics, you know, from previous studies, from Fourier analysis that you've done in, in, in mathematics or, or in a control system theory that fourier, fourier analysis, basically decouples a signal into several components which are at different frequencies, now, in, in typical fourier analysis and we talk about harmonics.
These different frequencies are always integer, multiples of fundamental in this case, you are not talking, talking about integral multiples of the fundamental frequency.
What we're talking here about components which are all of different frequencies.
And when they are put together, they form the overall system response shown with the red line in the bottom right hand side corner.
If you look them individually, they all behave differently.
So when you look all these three, constantly in part of the total response.
Since they are all positively dumped and oscillatory, the overall system response will be positively dump.
And the frequency of oscillation will be, a combination of all three minutes.
If one of these oscillations is unstable and growing, then that one will start to dominate overall system response after several times.
So, after they other modes are completely attenuated, following the following is the number of specific amount of time, the one which is constantly growing.
Will start to dominate overall system response and this is another example when we have more, more oscillations, more modes and you can see that depending on which mode we have, we have here one, two, three, four different modes.
So, when all four modes are put together, we have a response which is highly complex.
This is the red, the sorry, the black response in the middle of the second row of figures.
And it is a combination of all three modes.
They, the higher the value of real parties.
So minus one for example, is the red one over which is the bottom left hand side corner, of the slide this is the most dumped mode, the most dumped oscillation because it disappears in about a three seconds, roughly the first one, which has a real path that which is very, very small.
0.001 is the one which persists longest.
Now when we put all four together, what we can see that is that the resulting response, the one shown with a black line is very distorted and is becoming less and less distorted as the time goes by.
Why? Because within first three seconds, the fact of the mode four, the red one disappeared, so after the first three seconds the mode, the overall response, the combination on your three modes and then again as the time is passing by the influence of other modes, slow, the better dumped modes is disappearing.
Looking at a combination of only two modes just to see this more clearly, combining the most and we're the best and the worst damn modes, which is mode one and mode four shown over the black over the blue line in the right hand side corner of the slide, you can see that within, first three seconds we have a combination of two oscillations, combination of original blue and red line, which results in highly distorted oscillation during the first three seconds, after three seconds, the mode four is attenuated, so it's completely dumped, it disappeared.
So, the oscillations continue to be determined by the mode one.
This is why the least dumped eigenvalue is the one which actually determines the overall system behaviour, and this is why we're calculating smallest simple stability.
We always look which eigenvalue is the list dumped because this is the one which will last the longest end result in oscillations of the system which are practically dominated by it.
All other modes which are better dumped will disappear during the first part of oscillations that's why we're always on the lookout for the least dumped electromechanical mode.
And these are some examples of, of different responses depending on the values of individual components coming back to recapitulate on this effect of different parts, of the eigenvalue and why the eigenvalue is, is so important for small disturbance estimate for determining small disturbance stability.
Once again, if the eigenvalue is real, that will result in non oscillatory mode and if it is real and negative, we have decaying mode so it's exponentially decaying mode.
If the eigenvalue is real and positive, we have a periodic instability or exponentially increasing mode.
So I'm talking about a mode about individual component, and there may be n components in a system with n with a state matrix, which is n*n and state matrix will be n*n if there are n differential equations in the system.
So, the size of state metrics, once again is determined by the number of differential equations used to describe the systems.
So, if we had six differential equations to describe the system, the state metrics will be of the order 6*6 and consequently there will be six eigenvalues, six eigenvectors, six left and six right eigenvectors.
So each of these eigenvalues or mode as we are discussing it here, will have its influence in the overall system responds as shown with the equation in previous slide that we discussed.
So by looking each individual mode, we can decide how that mod will behave depending whether it's real or complex number.
So as I said already, if individual eigenvalue is real, then depending whether it's positive or negative with time it's a fact will be either exponentially increasing or exponentially decaying behaviour.
If eigenvalues are complex, then the response will be either oscillatory, dumped oscillations or increasing oscillations.
Oscillations will be dumped, if the real part of the eigenvalue is negative and oscillations will be increased with increasing monitor, if the real part of the eigenvalue is positive.
So when you take all these individual eigenvalues and put them together, it's clear that if there is a single eigenvalue which is real and positive, or if there is a single eigenvalue which is complex but with a positive real part, that will result in unstable response.
And that response will be either aperiodic instability or oscillatory instability, as the time goes by.
So when we are deciding when the system is going to be stable or unstable, the key thing is to find out - is there an eigenvalue which has positive real part or if it is real eigenvalue if it is positive.
If there isn't such eigenvalue then the system will be stable.
Now, the stability of that system will clearly be determined by the - with the smallest eigenvalue.
The eigenvalue which has the smallest real part, or the eigenvalue which is real and is, as such, the smallest number for eigenvalues.
So that will determine how quickly the oscillations will dump or how quickly the response will dump.
In classical - in typical systems - power systems, obviously, the least dump eigenvalues will be eigenvalues associated with the movement of rotors, which are obviously, electromechanical modes.
That's why they are called electromechanical because they are associated with electromechanical oscillations.
So the electromechanical modes will be the ones which are least dumped, and they will typically persist the longest.
Now, once we identify that, once we clarify, why do we need to calculate eigenvalues and eigenvectors? I hope it's clear now, so they are essential for determining how the response will look like without actually having to produce that response.
Because we can say how the response will look like simply by calculating eigenvalues.
Because if they are all positive or all negative, or there are some positives and negatives that will determine how the overall system responds.
I already said, that the overall system response will ultimately be guided by the behaviour of the least dump mode.
Guided means that it will last longest and therefore the overall oscillation of the rotor will be guided by the frequency of the least dump mode.
So if the least dump mode has a frequency of 1Hz then after certain time, the overall response of the system will be actually at 1Hz.
So the oscillations at 1Hz, because that is the oscillation which will last the longest and therefore determines the overall system behaviour.
Now, one point that we you can mention here is how do we determine which one of the many eigenvalues that we calculate for a multimachine system actually will be the one that is important to look at.
Typically, if there's an eigenvalue which is about six times, whose real part is six times, six or more times larger than the real part of the other eigenvalue, that eigenvalue with a larger real part will not be that influential.
So the critical ones are those which are six or more times lower than the rest of the eigenvalues.
So if you have say, seven eigenvalues all together, which means that the system had seven differential equations or the state matrix had seven by was over say, seven by seven, so in the system, it's seven eigenvalues, if there is - if there are two eigenvalues whose real parts are relatively close and more than six times smaller than the real parts of remaining five eigenvalues, then these two will be the ones who determine overall system behaviour.
And these two are termed as critical eigenvalues, and they should be studied.
In a multimachine system it's not often - doesn't really matter how big the system is, but the number of critical eigenvalues is not excessively large, depending obviously, how big the system is.
But in most cases, we are talking about very few oscillations which determines the overall system behaviour.
Very few oscillations meaning very few modes.
So at the end we end up having to stabilise three or four eigenvalues in total for a whole system to be stable because most of the others would be better dumped.
Now, one thing is to determine how the system response will look like.
And the other is OK, if the oscillation is there - if the oscillations are there, what can we do with them? You know, we don't want them to last forever as I said before, we typically like these oscillations to disappear within five to ten seconds at most.
In large systems, we can tolerate maybe 10 to 15 seconds, but again, this is not something we really like.
We would like them all to disappear in less than ten seconds.
Now, in order for that to happen, we need to find out - how can we do that? So, one of the ways of doing it is to find, what is it that influences particular mode, because you may determine that in a system with ten differential equations - ten modes, there are one or two eigenvalues which are either unstable or poorly dumped.
Now, these ones which are unstable or poorly dumped would need to be somehow stabilised.
But in order to stabilise them we have to determine first, what is it that affects them.
So one way of finding that is to calculate eigenvalues sensitivity and the formula for calculating eigenvalue sensitivity is shown at the top of the slide.
So as you can see this eigenvalue sensitivity can be determined as the derivative of state matrix with respect to the element of state matrix.
This unfortunately, is not very helpful, because the element of state matrix is not really what we can control, because the other developing mathematical model and performing Gaussian elimination, the state matrix - it elements became so complex and start involving various different system component.
We cannot actually trace, which particular physical component of the system is contributing to particular element of the state matrix.
So in this example, if you look there is the relative of state matrix 'a' with respect to a particular matrix component 'akj', now we actually don't know what 'akj' is.
We don't know which real network parameters are involved there.
Are these machine parameters? Are these line parameters? Are these transformer parameters? Because through a process of Gaussian elimination, 'akj' becomes combination of various machine and other elements - components, and we lose track of it.
So, if - even if you find out that the particular eigenvalue is extremely dependent of the state matrix element, say for example, 'a23', it doesn't help us much because we don't know what affects 'a23'.
So we have to find some other way of determining how a particular system components - realistic system components affects particular mode, in order to be able to control that mode.
Now, that is done using another mathematical term or another component from a linear algebra which is termed participation factors or participation factor.
Participation factor is a product basically of left and right eigenvectors.
So this is again, why we do need to calculate both left and right eigenvectors in addition to eigenvalues.
Initially I said we need them.
So, if we can describe system response without actually having to plough that response.
But as you can see, not only that base on eigenvalues.
We can determine whether system response will be stable or unstable, oscillatory or are periodic.
Eigenvalues and eigenvectors can be used for, for other conclusions that are necessarily about this instability or improvement - improvement of sustainability.
So, back to participation factors.
They are calculated using this formula on the, on the slide.
And as you can see they are product of left and right eigenvector.
Now, left eigenvector and right eigenvector, w and v.
Let's talk first about right eigenvector.
So, right eigenvector basically measures the activity of the state in the mode.
And this is something that was used, prior to roughly 1980s, mid 80s of the last century, when participation factors were for the first time use to perform model analysis in in power systems.
So, prior to that we were typically using right eigenvectors to determine how much particular state variable, is involved.
Let's use that phrase - involved with a particular mode.
This was not good enough because involvement with the mode, doesn't actually defines, how significant that involvement is.
That's why we have left eigenvector w, which actually weighs the contribution of this activity to the mode.
So, right eigenvector only tells us that a particular state variable for example, particular angle of a particular generator, is very much present, in eigenvalue seven.
However, that presence of the angle, of generator two in eigenvalue seven, doesn't weigh, doesn't measure how much of this presence is reflected, on eigenvalue seven.
This is where left eigenvector comes into play and, quantifies that involvement.
So, the product of the two, the involvement itself, as and the quality of the involvement, tell us what is actual contribution of angle of the generator two, to eigenvalue seven to use it as an example.
And this is what exactly we want to know.
Because if you find out that that particular eigenvalue is unstable, what we want to know is, which machine is involved with that eigenvalue.
And this is what participation factor will tell us, in electromechanical modes, the ones that are typically least dumped in the system, and the ones that involve movement of the generator rotors.
The typically most involved state variables, would be rotors and speeds of different generators.
So, by performing participation factor analysis, we are actually looking for, angles and speeds of individual generators in the system, that have high participation in unstable, or poorly dumped eigenvalues.
In order to do that obviously we have to calculate participation factor for all relevant, for all relevant eigenvalues.
Now, in a system with 10,000 or 100,00 differential equations, as would be for example European system, we will have 100,000 eigenvalues.
Now that is horrible number, huge number.
So, we can't calculate participation factors for all of them.
The first thing is determine, we try the relevant ones and obviously by reducing the, all eigenvalues calculated to only those that are critical, those that are least dumped, that number can be very very quickly reduced to, in realistic systems even even though even the systems like European ones to very few, very few eigenvalues.
And then we calculate participation factors for each of those eigenvalues that are suspected to be electromechanical modes.
How they are going to be a suspected to be electromechanical modes, we'll talk about that in a, in a minute or two.
Right? So, once we calculate, participation factors to determine which state variables are involved in which mode, that only brings us closer to, doing any action related to stabilising the system.
So, with eigenvalues once again, it's very important, that's why I keep repeating this stuff.
So, one thing is eigenvalues, calculating eigenvalues it will tell us whether the system is stable or unstable.
And based on imaginary part of the eigenvalue, we can determine what will be the frequency of oscillation.
The next thing that we have to do is determine who contributes, which system element contributes, which generator basically contributes to that eigenvalue.
And this is done through participation factor analysis, by looking in which of the suspicious eigenvalues.
Suspicious meaning the eigenvalues that are expected to be electromechanical modes.
And I'll come to that again in a, in a minute or two.
So, which of the generators is involved in these modes? Because these are electromechanical modes and involve movement of the rotors of the generators.
We are clearly searching for involvement of either speed or angle, of system generators into that mode, so we can determine that.
And then we can find out that in a particular poorly dumped mode, there are few generators that are involved with it.
That are contributing to it being poorly dumped.
The next question is okay, if you are to apply now some, some technique to make this mode better dump, because if we stabilise or improve dumping of that particular mode, which is the least dump, the overall system responsible improve.
As you remember, the overall response will be eventually driven by the behaviour of the least dump mode.
That's why we are so much interested in this least dump mode.
In order to find out where or which of the generators should be actually acted upon, to stabilise the mode, we have to use another quantity, which is, residues - residues of the system transfer function.
So, by calculating the residue of the open loop transfer function of the system, we can, using this formula here, we can determine which location is actually the best for dumping the mode.
So, eigenvalue will tell us whether the system is stable or unstable, and if it's stable or unstable, which is the critical mode.
Participation factors will tell us which generators are involved, in that particular mode, And then transfer function residues, will tell us which of the generators, involved in the oscillations, are the ones that will actually, be best place for stabilising that particular mode.
 
Large System Applications, automated transcript 018-10-12 ---  
LECTURER: 
So this discussion about Different elements of control system theory, Or linear algebra, residues, Eigenvalues, Eigenvectors, Participation factors, transfer function residues, These are all components which If we have to calculate them independently, If we have to write our own code to calculate them, Or if we have to learn how to do that, Would be a very challenging and demanding task, And this is once again what makes Power System Dynamics, Or used to make it even more complex than it actually is, Nowadays this is something that we actually don't have to do, Because many of the commercial available packages can do that for us.
Our task would be to understand what these quantities are telling us, And how to use them.
So before we move on to applications to our larger network, And calculation of these parameters in our larger networks, And before I finally specify what is the range of Eigenvalues that we are actually interested in; What all these add to mechanical modes.
How do we identify them without actually having to calculate all of this.
Or at least have some hunch which ones of many Eigenvalues to calculate, or the ones we should be focusing on, Let me repeat once again, because this is extremely important that these elements all play their role in identifying, Identifying the status of the system, whether it's stable or unstable, The main feature of potential system response if subjected to disturbance, The main contributors to that response, And the location where the action should be taken to improve eventual system response.
And that is why we need Eigenvalues for telling us where the system is going to be stable or unstable, And at what frequency it will oscillate once disturbed, Then it's participation factors to tell us which of the generators in the system are involved, Are oscillating at particular oscillation at particular mode.
We need residues to tell us which of those generators involved in the mode will be the best location to install control or to do something with them, to make sure that that mode becomes better damped.
Now, that's all easily said; and it's reasonably not exactly straightforward.
But it's reasonably straightforward if we're dealing with a small system.
If we have a single-machine infinite-bus system, and if that generator is represented by, say, constant flux, Constant extension model or constant voltage model, the model which has three differential equations, These three differential equations will be excitation voltage, Will be speed, and angle of the generator.
So the system state matrix would have three differential equations, It will be of the size three by three, Because the matrix is of the size three by three, There will be three Eigenvalues. It's very simple.
However, in multi-machine systems, when we have many machines, When we have controllers of these machines, either governors, which as I said, even though they are not typically modelled in the systems the I will say this, Sometimes you have a model which involves models of governors not only for dynamics, that is even for other standards and then you calculate Eigenvalues for that system, You end up obviously with a state matrix which is much bigger.
It may have, and typically has, AVR and Power System Stabilisers models in it.
If you have dynamic loads, it will have some flux devices, a high voltages, DC controls and so on and so on.
So the overall number of differential equations used to describe the system may be very large.
And the number of differential equations determines what will be the size of system state matrix.
So if there are 100 differential equations, The size of the system state matrix will be 100.
Therefore, there will be 100 eigenvalues, 100 left and 100 right, Eigenvectors and so on and so forth.
The key question now is, when we put this system together, Each of the generators has it's own rotor angle, And this rotor angle is, as we said before, power angle, is the angle between the terminal voltage for our practical purposes, between the terminal voltage of the generator and internal EMF induced in the generator by the excitation.
Now when we put all these generators together, The we can not work with angles, which are defined with respect to each terminal voltage of each generator.
So we have to come up with some common frame, And this slide here shows how this common reference frame is derived.
The common reference frame means that all the angles are measured with respect to a single reference value.
And that reference value is the axis which rotates at synchronous speed.
And as you can see shown here for one generator alone, We see that there is additional, the angle delta now is the angle which is not the angle between the terminal voltage of generator V, And excitation voltage which is along Q axis, It is the angle between the reference R and the Q axis.
So this is additional angle which is involved with this.
And this angle theta here shown in purple, Is different value for each of the generators.
So each generator has its terminal voltage at different position compared to the common reference frame.
So when they produce angle delta, this is not internal angle of individual generator, This is a angle measured with respect to common reference frame.
This is very important to remember because in many sophisticated control applications, we need to use actual internal angle of the generator; so that is not what many of the software packages will give us.
Many of them will give you the angle delta as shown in this slide, which is not exactly the internal value of the generator.
Now when we look the overall model, what does it consist of? Each of the dynamic devices in the system, So each of the devices which is described using differential equations will have it's own linearized model.
So which is one at the top.
Now when we put all of these state equations together, We will end up with a model which is now a little bit more complex Where AD is a matrix which is a block diagonal matrix.
Where at the main diagonal you have individual state matrices for each of the individual dynamic components.
Now, the linearized model of each dynamic device is in fact linearized model of each generator, linearized model of controllers, linearized model of high voltage DC controllers, For example linearized model of dynamic loads.
When we put them all together, we end up with a second set of a state space model, one which has index D, Where A, B, C and Y with index D, capital D, Are all block diagonal matrices.
These are just dynamic components put together.
Obviously, these dynamic components are not sitting in a isolated space; they are connected by transmission lines and transformers.
So they are connected by a transmission network.
Now, transmission network, interconnected transmission network is defined by another set of equations typically connecting currents and voltages obviously to a system transmission matrix, So these now, when they are all put together, and combined, We end up with a different system state equation which is shown, Where matrix A is complete system state matrix, And is, if you look matrix A there, the one which is encircled in the bottom of the slide, It consists of various different matrices that feature in previous sub-models if you like.
Now if you remember when I was talking about Eigenvalue sensitivity, I said that calculating Eigenvalue sensitivity with respect to system state matrix component is not very useful because we lose track of which actual physical system component is in moving that system matrix element.
This is explanation for that.
So if you look the composition of system state matrix a at the bottom of the slide you can see that it involves practically all differential equations, all components of the system differential equation is given by ad which is a block diagonal matrix as I said.
It involves input and output Bd and Cd connecting equations anything to it involves system equations Yn and Yd, so all this together.
When it's all squeezed together we get a system state matrix which now losses will lose the track of which generator or which dynamic load or which network component is involved in which individual state matrix element.
Therefore, calculating eigenvalues derivatives with respect to state matrix element doesn't make much sense or it doesn't make sense but it doesn't contribute to what we want to find out.
So one thing to remember there are different ways of describing this matrix formulations for linear systems they're shown here just for your information and if you pay much attention to it.
It's just the way how it made this appear in different books and different research papers when...when people are explaining the creation of complex model of a large system.
The more important thing to remember here is that we look when we look these matrices how they look like.
This is a system Jacobian matrix where you can see that in overall system matrix.
So ja in this particular this is adopted obviously for some old very old publication and individual when I said in our previous discussion that ad matrix is the metric which is block diagonal matrix were individual dynamic components are shown along the main diagonal.
So our ad from the previous slide is actually Ja here.
So where you can see each of the block it's of the shaded blocks in the top left hand side corner of this slide is...is a model as the dynamic model is individual components.
We have synchronous machines, induction motor or static compensators or dynamic loads.
All others are actually connecting equations between different components in the system.
And when we look the system state matrix for this is example of 39-bus and a 100 generators system.
This is the matrix which is obtained after putting everything together let's go one step back.
Before...before we apply Gaussian elimination before we create overall system matrix.
This is what you see in the screen here is the composition of the components of different system matrices.
When they are not merged together.
So you can see there is only elements only components with the shaded area are where we have nonzero elements.
So this representation is very sparse very easy to calculate using computational tools based or developed for calculation of sparse matrices part systems.
Once we perform Gaussian elimination once we squeeze network components connecting equations into the matrix which contains only dynamic equations only departed with differential equations.
This matrix ceases to be sparse.
And it becomes much more computationally demanding to calculate the values for that matrix.
Now when I'm talking about this computational demanding you may think so why is that so important.
It cannot be really a big problem.
Well, actually it can because as I said the realistic size systems like European system for example there are people who are running studies video appeal system may have in excess of 100,000 differential equations.
So this matrices we are looking now these moons parts matrix here.
May be actually 100,000 by 100,000 matrix.
So finding and computational methods to calculate quickly eigenvalues for that matrix for example, is very important thing.
Now this is example of ways how this can be done by different factorization.
And using different computational tools to facilitate fast calculation of eigenvalues and other parameters of these matrices just as an illustration.
And there are different techniques used to do that.
Which is as I said beyond the scope of our discussion here because this is something which is already built in softwares, which we are using for calculation of eigenvalues and other and modal analysis in general.
Now the key thing now that we have to come back to is these electromechanical modes.
So when we calculate eigenvalues of the system.
Typically the least damp or poorly damped oscillatory modes can be grouped in three or four categories.
There are electromechanical modes, control modes and torsional modes.
Now electromechanical modes.
The nodes that involve movement of the rotors or generators are characterised by frequencies between 0.2 and 2.5Hz.
In only...only in some extreme cases with very light generators we can have electromechanical modes with frequencies above 2.5 and they have been recorded cases where we have individual electromechanical modes with a frequency of about 4Hz.
But typically this is between 0.2 and 2.5Hz.
Now within that range 0.2 to 2.5 are all electromechanical modes and then can be further they can be further grouped into different subgroups.
If you like local modes, interplant modes and inter area modes.
Now the inter area modes are the most troublesome one but we will come to a little bit later.
So in addition to the group or three subgroup of electromechanical modes as I said local modes inter machine or inter plant and electronic and inter area modes we have control modes and we have torsional modes.
Now control modes which are associated with system controls typically AVRs and high ridge high voltage DC or static VAR compensator, SVCs modes.
They are characterised with very low frequencies typically about 0.1 or most of the time below 0.3Hz.
Now control modes are also typically at least with a very good damping They are very good damping compared to damping of electromechanical modes.
but very low frequency.
The depth the problem with them is that once we start acting upon electromechanical modes trying to stabilise them.
Because as you saw before as I said before electromechanical modes can have frequencies in the range 0.2 to 2.5Hz.
And control modes can have frequencies below 0.3.
So there is a slight overlap between these two groups of modes.
So if we try to stabilise one of them say electromechanical modes we may interfere with the other ones with the control modes because of this frequency overlap.
And this interaction typically is such that while we are improving damping of one like electromechanical, we are deteriorating damping of the other the control mode.
So basically damping of electromechanical mode becomes better and it starts moving further to the left in a complex plane so away from stability limit.
While at the same time damping of the control mode becomes worse and it start moving to the right.
So closer to stability boundary so there have been cases in...in real life where the improvement of electromechanical mode resulted in loss of system stability through unstable control mode.
Initially control mode will stable and much better damp then electromechanical mode.
While you were improving the stability of the electromechanical mode, we took the eye off the control mode, and control mode effectively, run away to the right, cross this boundary, and destabilise the system.
The third group of modes, torsional modes are only observable.
They do exist in the system, but they are only observable in our mathematical simulations, if we model multi-stage turbines, and they are associated with a mechanical oscillations, of the shafts of turbo generators, because as I said, in, in discussion, of the modelling of synchronous machines, the turbo generator cylindrical autogenerator, is driven by steam turbines, may have a very large multistage turbines attached to them.
And I said that these mechanical system, consisting of a multistage steam turbine, and generator can be as long as 30, 40m.
Now, that system, will have several concentrated masses, along practically the same shaft.
So when disturbed these masses start to oscillate, start to move in different directions, at different frequencies.
So we can see, basically the shaft twisting at different frequencies.
These are the torsional oscillations.
These modes are typically, are occurring at higher frequencies, that their characteristics are frequencies.
We try between five and 50 Hz, so they are outside the range of electromechanical modes, but these are the modes, that we can typically see in, in the eigenvalue chart of the system.
So once again, the three typical groups of modes, which typically is poorly dumped in the map, eigen value map of any system, with the electromechanical modes, control modes and torsional modes, control modes, would typically have the lowest frequency of the three, typically lower than 0.3.
Electromechanical modes, will be in the range from 0.2 to about 2.5 Hz.
And torsional modes would have frequencies, in the range from about five to a slightly below 50 Hz.
The group of electromechanical modes is typically, the group of modes which are the least dumped.
And within that group of electromechanical modes, we have further subdivision, they have subdivision to local modes, inter machine or interplant modes, whose frequencies very often overlap, which goes, because that depends on how many machines are involved, for individual local modes, when one machine oscillates against the rest of the system.
The frequencies are typically one Hz, though it may range from 0.7 to 2.5.
When we talk about intermachine, or interplant modes where a very few machines are involved, because more machines are involved, the frequency would tend to be slightly lower, but that doesn't have to be the case, because we may have a very light machines, but the number of them.
And then the frequency will not be that low anyway.
So that's why it's very difficult to tell, whether the particular mode is intermachine, or interplant mode or whether it's a local mode.
So their frequencies are the same, and the most troublesome one, are inter-area modes, which involve a large number, of machines oscillating against each other.
A large group, two groups of machines oscillating together, often they have half of the system, oscillating against the other half of the system.
In a very large system, these electromechanical modes can be, can have very low frequencies, lower than typically 0.5 though, typical range will be between 0.2 and 0.8Hz, but we can say we can have again, depending on how many machines are enrolled, how large our system is.
That can range from anywhere, from 0.1 to about 0.8Hz, depending on the size of the system.
Now the thing with the electromechanical, over the inter-area mode, the critical problem with them, is they involve a very large number of machines, and it's very difficult to stabilise them, because it's not one machine that oscillates.
It may be 50 machines in one part of the network, oscillating bar against another 30 in different parts of the network.
So how do you stabilise that, by applying a single controller is a big problem.
One thing that we haven't that I haven't mentioned yet, is how many of these electromechanical modes, we are expecting to see.
Because I said before, we can calculate toward the eigenvalues, we have to identify electromechanical modes, and now we know how we can do that.
We can search for modes who's frequencies are in the range of 0.2 to 2.5Hz.
But again, if you search for these modes, you may find some of them being electromechanical, and some may be control modes, and then maybe some other modes, because from one system to the other, you may have some other modes, whose frequency may fall in that range, the first thing that we have to distinguish here, is that in a system with n machines, they will be n-one electromechanical mode.
So if the system has 10 machines, there will be 10, but there will be nine modes, nine modes because one machine can not oscillate against itself.
So the oscillations are always shown with respect to other machines.
So two machines, one electromechanical modes, three machines two electromechanical modes, 10 machines, nine electromechanical modes, and so on.
So in a system with say 10 machines, we know that they will be nine electromechanical modes.
Now these nine electromechanical modes, would be always the modes frequencies, in the range with a 0.2 and 2.5Hz.
We may actually have more eigenvalues, who's imaginary part, so the frequency is in that range.
That's why we need to do a participation factor analysis, because participation factor analysis, will tell us individual those, modes whose frequencies are between 0.2 and 2.5Hz, in each of those modes.
The participation of angles, or speeds of individual generators is the highest, only those modes where angles, and speeds are participating a lot in our, the electromechanical modes.
Some of those modes who's witnesses may fall in this range, may not have participation of angles and speeds at all in them, so these would not be electromechanical modes.
These will tend to be control mode.
Obviously sometimes they may not be stable, and they have to stabilise them, but in typical systems with the typical parameters, the modes which are pulled the damp, the least would be the electromechanical more, than we have to focus on them.
This is example of eigenvalues spectrum, of a very large system without any control.
So as you can see there are, this is the stability boundary, where there's a blue line is the ellipsis.
So what we have here, we have a system with a 1,676 states, meaning 1,676 eigen values, and some of these eigenvalues are obviously unstable, and they have damping ratio, which is unsatisfactory with damping ratio was defined, one of the previous slide, as the ratio between the (INAUDIBLE) eigenvalue and its real part, and as long as it is a lower than 5% line, which is shown on this slide, we deemed this oscillation to be in adequately or poorly done.
So in this particular case, we can see that the system without any controls, has about one, two, three, four, five, six, seven, eight eigen values, which are poorly dumped, four are poorly damped and four are unstable actually, because they are on the right hand side of the stability limit, which is, this zero line in the complex plane.
So this is a complex plane.
Top part is positive button, part is negative.
And then left is again negative and right is positive.
This is positive and negative frequencies it's automatic.
Automatically plotted, using one of the commercial software packages.
But as you know frequency can not be actually negative, so what we typically do is we only plot the second quadrant, which is the one with the positive frequency and - and negative damping.
But this is the way how the software sometimes produce that so we cannot have a eigenvalue which - whose damping is say, -01 and frequency is -1Hz.
That's not possible, so that's why we don't have to pay attention to the third quadrant which is the bottom left-hand side of this diagram.
Now, this is example, how this response of the system without controllers looks like.
And as you can see, there is a mess of different oscillations and there is a number of them which is growing as the time is passing by.
We could expect this to happen because as you saw, we had four eigenvalues which are on the right-hand side of the complex plane, which means - which are unstable.
Once we applied controllers to the system, we can see that all eigenvalues are practically shifted to the left of this 5% line.
So the system is now stable.
We have some modes which are still relatively close to stability boundary but none of them is on the right-hand side, so the system is overall stable and this is the response of the system.
So when you look at this, you can see that after about ten seconds, we are getting - oscillations disappear.
So this is what I said before, ideally, we want these oscillations to disappear within about five to seven, eventually, ten seconds.
In a very large system, we can tolerate slightly longer times with oscillation maybe up to 15s.
But anything - anything shorter than five seconds would be practically impossible in very large systems.
And we can see here that after applying controllers, the oscillation is successfully stabilised within as I said about ten seconds.
They still have to return to a steady state but there are no oscillations any more, at least.
Now, this is example of these oscillations in European system, as you can see, this is a map of continent of Europe, and these two red lines, one between Spain and France and the other across Poland, Denmark, Germany and Austria and Slovenia, shows how these three part of Europe - the generators in these three parts of Europe oscillate against each other.
Now, before, I said that we have these different tools or attributes or whatever the right word for that is, mathematical measures that we calculate to determine system behaviour without actually having to produce responses, namely, eigenvalues, eigenvectors, participation factors, transfer function residues.
And I said that, prior to using participation factor analysis which was used to determine which generators are involved with each eigenvalues.
We relied a lot on calculating right eigenvectors because right eigenvectors will tell us how much particular state is involved in particular mode.
Once again, that is what all the right eigenvectors tells us.
The left eigenvector measures the quality of that involvement.
Now if you now focus with some right eigenvectors alone which are plotted here, right eigenvectors.
Eigenvector for any of 'n' eigenvalues is in 'n' by 'n' system, will have 'n' components.
So, eigenvector is a vector with 'n' elements, and each of the eigenvalues will have one such corresponding eigenvector.
So, eigenvalue one, will have right and left eigenvector and each of these eigenvectors will have 'n' components.
Component of each - each component of these eigenvectors corresponds to one of the system state variables.
So among the components of the right eigenvector we can identify those that correspond to speeds of individual generators.
So if we have a system which has five generators and if each generator is modelled by three differential equations, they will be all together 15 differential equations in the system state matrix.
So the size of system state matrix will be 15 by 15.
There will be therefore 15 eigenvalues, and each of these 15 eigenvalues will have its corresponding left and right eigenvector.
So, for example, eigenvector one - eigenvalue one will have a right eigenvector one, and that right eigenvector will have 15 components.
Three of those - sorry, five of those components will have - will correspond to speeds of five generators involved in the model.
So if we plot this five components of the eigenvector that corresponds to speeds of these five generators because they are complex numbers as well, these components of the eigenvector, they will have a certain position, if you like, in the complex plane.
So this is a complex plane here, where each of these lines represents magnitude and angle of the component of the eigenvector that corresponds to a speed of a particular generator.
So what we can see here, that for eigenvalue whose real part is -0.20045, and whose imaginary part is 1.4648Hz or 0.03Hz because this is given in per unit, so, 1.465 is in radians.
So once divided by 2π we get the value in Hertz.
So 0.03Hz at this mode, we have by - a modal plot that shows which generators are involved in it and how they oscillate against each other.
So what we can see is that generators in Spain and Portugal, these green eigenvalues on the left, and generators in France, the purple ones are practically oscillating against the blue ones and greens ones and dark, well dark-red ones which are generators in Poland, Germany, Hungary, Czech Republic, Slovenia, Austria and Croatia.
So, this is how the whole part, one part of the Europe - one part of the generators, in one part of the Europe is oscillating against generators in the other part of Europe.
And then we can do that for other modes, so this is in a different mode at 0.3Hz, again, we can see how different generators are oscillating against each other.
So the - and another plot similar to that.
So the thing that we have to remember here is that plotting the appropriate components of the right eigenvector, the appropriate component is the component of the eigenvector that corresponds to a speed of the generators involved in that particular mode, will give us a mode shape.
So these diagrams - these diagrams here are actually mode shapes because they tell us which generators are oscillating against which other generators.
So right eigenvectors are still very useful even though they do not tell us exactly how much particular generators are involved in particular mode.
They give us the picture the visualisation or how the system is actually oscillating, how the generators in the system are oscillating.
And coming back to inter-area oscillations once again, because they involve so many generators, if you go back and look at this previous mode shapes, that I've shown you for European system, we have many, many, many, many generators, from different countries, involved in a particular mode.
Now, in order to stabilise that mode, it would be unrealistic, to assume that we can do that by installing power and stabiliser, as most widely used power system control at any single generator, because there are so many of them involved.
So it requires more than one stabiliser, to bring the system together.
The, the other thing with inter-area oscillations, why they're so complicated to, to control and why they are, they have been and still are, a subject of research and investigation is, because they are spreading across the system.
There are many other, elements in the system in particular system loads, that influenced significantly inter-area oscillations, because depending on system loads, which are spread across the system, we may have different effect on power transfers, and therefore different effect on system oscillations.
Now, if, you haven't get it yet, because I wasn't explained clearly, I want to repeat once again, say how these electromechanical modes, how this system oscillations, are actually manifested in real system? I've been talking all the time, until now about rotors, of generators oscillating against each other, or rotor generators and oscillating against the whole system.
Yes, that is the case the rotors are oscillating.
The rotors are not moving smoothly at 50Hz.
There speed is actually trembling around 50Hz.
That's why we have these oscillations, but we do not measure that, we do not detect electromechanical mode in the system, by measuring rotor speeds, we detect them by observing, power transfer across interconnecting lines.
So under normal operating conditions, the power transfer within two parts of the system, across the connecting line, would be constant.
So if we set it at say a 500Mw, that power transfer would be 100Mw, and it should be continuous 100Mw, if we observed that this power transfer oscillates.
So it's a varies between 90 and 110, as the oscillation goes up and down, up and down, up and down.
That variation of power transfer across transmission line, would be at the frequency of between 0.1 and 0.8Hz, and this is actually how we detect electromechanical oscillations, in the system and once again, the name electromechanical, is basically coming from the fact, that we have an oscillation of electrical quantity practically, which is electrical power, caused by oscillation of mechanical device, or mechanical component, which is the rotor of the generator.
So the mechanical movement of rotor, this is mechanical bit, results in the variation of electrical power across the system, which is electrically, hence the oscillation is term electromechanical, and it's observable, in real system as variation of power across transmission lines.
Now, if you imagine now if these installations, as I said before, these oscillations would have to be dumped, within maximum 10 to 15 seconds even in the largest systems.
Why? There are various reasons for that, but obviously if we allow the system to oscillate, for so long in the system oscillates, if you have a sustained, not sustained, but if they have oscillations for 10 or 15 seconds, across the transmission line, we may have during that period another disturbance, which may result in even higher oscillation of the power, in which case the protection, we may trip the line and we may, and the system as a result in a, in a collapse.
This was a case in one of the recent blackouts, which was in the United States about 10, 15 years ago, when basically the oscillations rest sustained.
And then subsequent disturbance, resulted in growing oscillations, and the protection (INAUDIBLE) aligned, and we had half of the Western United States, blacked out.
So the reason for, that's one of the reasons, the other reasons, obviously then oscillation will cause the rotors to tremble to, to, to not to oscillate smoothly for a long time.
So 10, 15 seconds, that's what long time is.
So these sustained oscillations, would cause additional stress, and wear and tear of the, of the machine itself.
So that's why this is another reason, why we don't have them, whether they want them to be a long lasting and frequent.
So the key thing to conclude about this, this discussion about interior installations is, it is not only that they are determined by the generators, and the location of generators, they are also strongly influenced by load characteristics.
They are influenced by tuning of system controllers.
Speed governors that I mentioned before, are they generally are not affecting them, though they mean to do some negative dumping as well, as may a fast acting AVR that I already mentioned before.
So controllability of these modes, with parts stabilisers is not very straightforward, because of the number of machines involved, and coordinated tuning of PSS is a different locations is required, which again is not a very, very straightforward method.
The ultra mechanical modes, are therefore or have been, attempted to be controlled, by controllers which are installed, close to those lines where we observed oscillations.
And that's why high voltage DC installations.
So converters, high voltage DC converter stations, and facts devices which are placed in the system, are found to be very useful, locations for installing this additional dumping controllers, because they are closer to the location of these oscillations.
So if there is a variation of power, across a particular transmission line, and if we have a, fax device closed to that line, clearly a very good location, for installing additional damage control, would be device, that can modulate power across that line, and stabilise the oscillation.
To conclude this discussion, about the size of the system, and the complexity of dumping inter-area installations.
This final slide, for this section shows you how big, the system matrixes are, actually in how many state variables.
We have for different realistic size system.
So you can see here, NORDEL system, which is a North European system, has about 12,000 state variables.
East Coast United States is 8,000, Latin America South-cone is 2,800.
So these are very, large state matrixes, as it's a very large systems.
And that's why when we talked about the ways of calculating, when I mentioned that there are different ways of calculating, I gave of such matrices, that's why it is important to have efficient ways of calculating, not necessarily all eigenvalues, but the critical ones.
And there are obviously mathematical methods, when you can guide the, the calculation of eigen values and, and do that in an efficient way, so that even the matrix may be very, very large.
You can, calculate only the eigenvalues of interest to you.
But again, this is, these are mathematical terms, which are not something that we're going to dwell on, as these are programs, typically built already or prepared for you in available, in available packages developed by clearly by mathematicians.
So you had in the previous chapter, how smallest living stability analysis is performed, both in a small system and in a large system.
Why we use a different mathematical tools for the analysis, and how these tools can be used to inform us, about systems stability and the areas where this, this disability can be controlled from, without actually having to perform transient simulations.
The next section we'll be talking about transient stability.
 
Modelling requirements for Transient Stability Studies, automated transcript 018-10-12 ---  
LECTURER: 
So we have completed the now three sections altogether the last one was about small disturbance stability following the introduction in modelling and we are moving now to transient stability analysis their principal difference between the previous one and this one is if we are dealing now with different disturbances while the small disturbance stability analysis is predominantly concerned about behaviour of the system following a very, very small disturbance around giving operating point.
A large disturbance contrary to that is when the system is exposed to severe disturbance either fold or lost of a large component then the movement from operating point typically results in oscillations which hopefully if stable will lead to system attaining another operating point which would be stable in order to do that we have to apply again some tools for calculation and some modelling which is different than the one that is described before and this is what this section will be about.
As part of this section, I will obviously touch a bit and discuss to some extent Equal Area Criterion as you have all heard about because Equal Area Criterion is the only analytical tool that we have for transient stability analysis which is widely use.
There are other methods I will talked about but they're not as widely use as Equal Area Criterion.
At least for physical explanation of what's going on in the system during transient disturbance.
So the next section therefore is the next chapter is about transient stability analysis of power systems.
We'll start with modelling requirements for transient stability analysis.
Now, transient stability analysis is characterised by a large disturbances.
So rotor, generator rotor angle changes significantly it's not any more small disturbance surround operating point it's a very large deviation fast acceleration and deceleration and hopefully this acceleration-deceleration results in attainment of new steady state.
Clearly, because we have here a large variations, large movement we cannot linearized the system anymore so we are not using the linearized equations around given operating point.
Post-disturbance operating state is usually very different from the pre-disturbance this one.
And the key thing for transient stability is here first swing stability which typically happens within the first one or two seconds and may be sufficient in some time when we can say OK even the system is first swing stable it will be stable at the end globally but that is not a guarantee for overall global system stability.
For global system stability, we would need to observe system behaviour for about 10, 15 seconds after the initial disturbance.
Now, major causes of system transient stability problems are as I said before power system faults, faulty synchronisation or connection of the generator to the system and asynchronous operation and resynchronisation of the generators following a disturbance so when generators are not operating at 50 hertz.
Obviously, in addition with the system faults we can observe we can consider not only say short circuits fault but it can be a loss of line, disconnection of lines or something along those lines.
So largest of us which really leads to big changes in voltages and power transfers in particular part of the system.
Now, the key question for transient stability analysis.
because we cannot use simplified models and mathematical answers the value of calculation is relatively fast and relatively straightforward.
Transient stability analysis in the other hand is typically done by performing numerical integration of a very large sets of differential equations.
If you remember from previous chapter when we discussed small distance stability I showed a slide at the end of that chapter which illustrates how big the system models are and there the models just saw in that slide range from few hundred to several thousand the differential equations.
Now imagine if you want to look transient stability analysis for 15 seconds we need to do 15 seconds responses by performing numerical integration of 20,000 differential equation this is something we've take a lot of time.
Now the key question here is what is the period of interest? So how long we want to do that as I said we tend to five seconds.
Now the next thing is depending on how much computer power we have and how quickly this should be done that also determines the way how we calculate this this transient stability performance of the system and these responses of individual rotor oscillations.
 
Examining Transient Stability through an Example, automated transcript 018-10-12 ---  
LECTURER: 
One thing to remember is to explain overall requirements and although physical processes that are involved with transient stability analysis.
We will do that through using a simple example and referring to equal area criteria because once we perform start performing numerical integration of differential equations, we cannot actually see what is happening with using very simple example of a single machine/infinite bus system again and relying on equal (INAUDIBLE) can explain processes that are actually happening inside the generator during the large disturbance and which resolved in overall oscillations of that generator and other generators in the system.
So let's consider a very simple system which has one generator connected to an infinite bus and a fault in one of the transmission lines.
So the first thing that they have to do is determine pre-disturbance operating state.
So pre-disturbance operating state is important because depending on where the generator is before the disturbance that will determine how fast it accelerate.
Now in this particular section I will very often refer to the swing equation.
So if you remember the swing equation is delta omega, delta t equals one over 2h PM minus PE h is inertia constant, PM is mechanical power and PE is electrical power.
Electrical power is given by the equation at the bottom of the slide EV over x sine delta, PE is internal voltage of the generator VE is the terminal voltage or the voltage between which impedance x1 is measured.
So impedance x1 is the impedance between voltages e and v and sine delta e is the sine of the angle between these two voltages.
So it's not the sine of the voltage angle of a particular voltage, it's the sine of the angle of the angular difference within the two ends of the line.
So the first thing is determine the pre-disturbers operating point which can be done using very simple equivalent circuit as shown at the top of the slide and that point is point delta naught on the diagram below which tells us where we are before the disturbance.
Depending where we are before the disturbance, we will accelerate differently.
So if you imagine that at the point where we are before the disturbance at the point PM, if the disturbance happens if it's for example three phase fault and if the voltage drops to zero then our acceleration will be determined by the difference between power before the disturbance which is PM which hasn't changed and power at the moment of disturbance which is electrical power now which is zero because the voltage dropped to zero.
So we will be accelerating the machine with power PM.
So initial operating condition of the generator is very very important for the acceleration that will follow after the fault.
If initial operating point for example, was half of the one shown at this slide then the initial acceleration obviously will be at a half rate because PM would be half of the initial value and then machine will accelerate much slower.
So by determining initial operating point we find out where the generator is, we find out delta naught angle delta naught where the machine is before the disturbance.
During the fault, electrical power drops to zero.
So electrical power drops to zero and in swing equation the difference between mechanical power and electrical power becomes very large because electric power is zero, so the difference PM minus PE which is accelerating power becomes equal to PM.
So machine starts to accelerate.
Now this acceleration will start to happen and then once we detect the fault and we disconnect the fault, the faulted line is removed.
Once the faulted line is removed then the impedance between the generator and the rest of the system changes because now we do not have two lines in parallel, there's only one line left, so in impedance actually increases.
This increase in the impedance in the post fault condition between the generator in the system obviously results in reduced power transfer.
Because if the impedance between e and v is a larger less power can be transmitted between these two points.
So our post fault characteristic shown with the purple line on the graph on the graph below is actually having the minimum value which is lower than initial power angle curve because the initial power angle curve was over the impedance x1 which involves two lines in parallel.
So plotting these two together we have a situation of the system in distinct snapshots.
So the blue line on this on the graph shows pre-fault power characteristic and dark green point indicates where the system was before the fault.
The fault happened, the power transferred drop to zero.
So red horizontal line at the bottom of the slide.
So during the fault we are staying along red line.
Once the fault is cleared, new topology in the network is created with one line disconnected.
So potential power transfer after the fault is given by a purple line.
And stable operating point would be a light green dot which is the location of delta one angle delta one.
So what we have in this diagram is indication where the stable operating point was before the fault that green light...
dark green dot and where the stable operating point could be after the fault which is a light green dot.
The question of trans instability is whether once disturbed with a fault three phase fault in this particular case, whether once disturbed when at green dot, the system will ever manage to reach light green dot.
So during this period we will have violent or less violent oscillations of the system and if everything goes well we will end up in a light green dot, if it doesn't, we may lose stability.
So the transient stability analysis deals with studying what happens when the system is moved from dark green to light green point as...as a consequence of a large disturbance and whether this light green dot or a second new operating condition will be ever attained.
So once again starting from the pre-fault condition.
So we are operating a dark green point the fault happens and the operating point of the system drops down to a red characteristic.
So at that point the balance between mechanical and electrical power of the generator is disturbed.
In steady state while you are operating at the green operating point mechanical power delivered by the turbine and electrical power demanded by the system were equal.
So the acceleration at that point was zero because PM minus PE is zero, so there is no acceleration.
Once fault happened at the beginning of the one of the lines, the voltage generator terminals practically dropped to zero.
So we can't deliver any more power to the system.
So electrical power became zero and the accelerating power, the difference between mechanical and electrical power now is PM minus PE equals PM.
So the machine starts to accelerate with a full mechanical power delivered by the turbine because turbine is not able to change its setting instantaneously.
So machine starts accelerates because mechanical power is e is larger than electrical and as you can see at the bottom the purple line moves to the right which means the rotor angle starts to increase.
At some point, we clear the fault.
So the rotor angle starts to increase, the protection system notifies the increased currents in the system and the fault is disconnected.
At the moment of fault disconnection we have reached some angle a moment of clearing so delta clearing.
Fault is disconnected and the operating point jumps again from zero power, zero electrical power to a new value of electrical power.
Now this new value of electrical power is determined by post-fault characteristic which as we said in the beginning is different from the pre-fault operating condition because in post-fault operating condition we have one line less in the system, so impedance of the system increased and the maximum power transfer during the fault after the fault is reduced.
Nevertheless, we jumped from zero electric power to electrical power which is now positive.
This operating point electrical power is a larger than mechanical.
So accelerating power Pm minus Pe becomes negative meaning that machine starts to decelerate.
That means that it will happen eventually if we have used all the accumulated energy during the fault.
At the moment of this connecting default.
It is true that our electrical power became a larger than mechanical.
So we are not accelerating machine anymore. We are slowing it down.
But during the fault the rotor was accelerating and a lot of kinetic energy was accumulated in the rotor.
So we cannot stop it instantaneously and turn it back.
So the rotor will continue to move to accelerate but at the slower rate.
So the accelerate there will be no acceleration anymore as such it will not be growing the acceleration.
The machine will continue to turn to move in the same direction but at the slow rate it's slowing down slightly but still moving in the same direction.
And that will continue until all accumulated energy is consumed.
So when we do that we have reached at some maximum value of the angle at the value delta max.
All accumulated energy between delta naught and delta clear has been consumed, have been dissipated.
And that dissipation is helped by the fact that between delta clear and delta max electrical power was larger than a mechanical power.
So during that period we were kind of braking slowing down the generator.
And at the point delta max we consumed all the accumulated electrical kinetic energy in the rotor of the generator.
Now at that point obviously the rotor of the generator, rotor angle of the generator rotor is not where it was before.
It's...it's stretched if you like to the right now if we...if we go back and talk about that spring from the first block of...of lectures.
So the spring our spring is extended now to the maximum.
If the synchronising torque is large enough and positive, the spring, the stiffness of the spring will pull the mass back or synchronising torque will now pull the rotor back.
And that actually will happen.
So the synchronising torque pulls the rotor back and the rotor starts moving now in opposite direction starting a rotor starts to return to where it was before.
Obviously because the inertia is involved it will overshoot.
The steady-state value it will go below pm and then go back again and then eventually it will settle, it will settle at new steady-state operating point.
And these are examples of rotor angle and speed responses in the system.
You can see equal area continue on the left.
So the acceleration period when the fault happens and then this which is the area a1 then this duration period which is area a2 on the left hand side.
And on the right hand side, you can see the increase in rotor angle and rotor speed as it happens during this fault.
So we have reached the new steady state and the system is clearly stable.
So this was possible because we managed to dissipate all accumulated energy during the accelerating period.
If that was not the case, we obviously wouldn't be able to return back to stable operating point and it would have lost stability.
Now that can be explained using a marble analogy.
So when the fault actually happened it looks like it can be looked at as releasing or letting the marble slide down the hill.
So while going down the hill, marble accelerates because it is subjected to a gravity.
This is equivalent to generator.
Generators rotor accelerating because accelerating power becomes positive pm minus pa remember, was equal to pm.
So the rotor was accelerating all this marble was rolling down the hill.
At the moment when the rotor reached, when the marble reached the valley the bottom of the hill, this is equivalent to the point when we clear the fault.
So at that point we clear the fault.
We clear the fault.
So we are not accelerating the rotor anymore.
In this particular case there is no hill anymore, so rotor is not accelerating anymore.
However, acceleration becomes negative as the marble goes uphill.
So it does not stop because it has acquired momentum it has accumulated kinetic energy by rolling down same as our rotor, rotor didn't stopped once we clear the fault.
Rotor continued to rotate in...in the same direction but slowing down and...and it goes up to marble goes up the hill here and the rotor went to value delta max until all accumulated energy y in case of marble rolling down uphill was consumed.
And then the marble goes again to down and settles down at the new...new steady-state operating point which is at the bottom of the hill.
So this is equivalent to what we had before with the rotor.
Now let's look at the case when angle increases beyond limit value.
So if we clear the fault, so the same scenarios before a dark-green point fault applied with dropped down to red operating characteristic so faulted line at angle delta clear we clear the fault.
So the operating point jumps from red characteristic to light purple characteristic.
We start decelerating the rotor.
And the operating point starts to move along light purple curve.
Now at the point of delta limit where the light purple post-fall characteristic crosses the pm characteristic by the time we reach that point.
If by the time the region point, we haven't the rotor hasn't dissipated all kinetic energy accumulated between the point delta naught and delta Claire, it will not stop.
It will continue to move in the same direction.
Meaning the angle will continue to increase.
However, once we passed the point delta limit what happens actually is that electrical power becomes smaller than mechanical power.
So the moment electrical power becomes more than mechanical power the acceleration becomes positive again.
Because Pm minus Pe becomes positive.
So the machine starts to accelerate again.
So we actually are not returning back.
We are adding more oil on the fire.
So we are accelerating the system further.
And the system then will lose stability and it will never return to a steady-state point indicated by a light green point.
Now this is not actually going to happen in real world because once the rotor accelerates beyond certain speed the protection of the system will trip the generator and we lose synchronising.
But this the example here explains what would have happened if the protection did not exist.
 
Equal Area Criterion – a tool for examining transient stability tutorial, automated transcript 018-10-12 ---  
LECTURER: 
So, returning to marble analogy in this particular case when we didn't dissipate all the accumulated kinetic energy after the fault clearance.
That would correspond to the case when our marble, which was rolling down the hill would reach the valley.
And then, start going uphill.
But because the cumulative energy was larger than the energy dissipated by climbing the hill on the right hand side.
The marble will come to a next top.
And then, it roll over down again.
Which it means it will never, never, never come again to stable operating point.
Which was the case in previous example.
Clearly, based on this we can see that there is a limit.
There is a limit which defines whether system will be stable or not.
And that limit is that maximum angle, maximum inclination of the rotor following a disturbance, should be less than the limit value.
The limit value of the angle.
What is the limit value? The limit value of the angle is actually the point where post-fault characteristic intersects with turbine characteristic.
The mechanical power delivered by the turbine on the right hand side.
Because there are two, obviously there are two intersection points.
One is stable the other is unstable.
The stable is in the left hand side, the less than 90 degrees.
And the unstable is the one with between 90 and 180 degrees.
So, the limit angle is the angle which is between 90 and 180 degrees on the post-fault characteristic.
If we manage to operate in such a way that the maximum angle of following the fault is less than that limit angle the generator will remain stable.
And this is the essence of defining equal area criterion basically.
That you heard about before.
So, to visualise that once again.
So, the first bit.
Again, the same characteristic.
Now, the areas of relevance are highlighted more clearly.
So, once the fall happens at the angle delta 0.
And the machine starts to accelerate before the fault clearing, we have this green area.
Which is here, marked as area 1.
So, we have the acceleration of the generator.
So, during that period between delta note and delta clear.
The generator is accelerating with Pm minus Pe.
Pe being 0.
So, the accelerating power is equal to Pm.
So, the generator accelerates all the time and gains.
It gains kinetic energy.
So, it, kinetic energy increases.
And the point delta clear, we remove the fault.
And the system jumps to post-fault characteristic.
Now, during that period, while we are operating along the post-fault characteristic.
We have a situation where we are slowing down the generator.
So, the area A2 corresponds to potential deceleration area.
So, as long as we are operating above the Pm characteristic on the light purple curve.
We are slowing down the generator.
So, the key point here is whether by the time we reach delta limit we will have consumed all the kinetic energy accumulated during the acceleration.
So, in order to find the answer to that question we have to check whether the area A2 is equal or greater than area A1.
So, if we do not do that.
If we move to passed delta limit point.
We have another area, area A3.
Which is again accelerating area.
So, the machine will start to accelerate again.
So, we are not going to reach any stable operating point.
Clearly, the criteria for having this situation under control is that accelerating area A is less or equal as a boundary condition of this accelerating area B.
And this is illustrated here for two examples.
One, where these two areas are such that A is less than B.
So, the stable system on the left hand side.
And the other one, where accelerating area is larger than decelerating area.
So, the system loses stability.
This is important thing to remember.
That's why I want to once again repeat some of the explanation that I have done before.
Because this is the essence of understanding what is going on in the system during the disturbance.
Actually, any disturbance whether it's small or large.
Here, we are using example of large disturbance.
But this the thing of gaining and dissipating energy is the same thing.
So, if you look again the left hand side.
What you can see when the fault happens at point 1.
And we drop down to point 2, the machine angle starts to increase.
At the point 3, when the fault is cleared, as I said before.
We are not changing the direction of movement.
The rotor angle continues to increase.
But as you can see the slope of that increase is now different.
Because we are actually breaking, we are slowing down the rotor.
And the point C.
Which is or 67 on the power angle curve above At the point C, on the rotor angle time curve, we have reached the maximum inclination of the rotor angle.
At that point, all the accumulated energy, which we accumulated while moving between points 2 and 3 in the power angle curve diagram.
All the accumulated energy during that period was dissipated while moving between points 4 and 7.
And we have reached maximum inclination at point C.
At that point the rotor angle starts to reduce.
Because we are returning back and eventually it settles at a new operating point.
On the right hand side, the example of unstable system shows that by the time we reach point C.
Even though we were slowing when moving from point 3 to point 8 on the right hand side diagram.
When we reached the point C we haven't dissipated all the energy accumulated during the acceleration period.
And at point C.
4.8 on power angle curve.
The mechanical power became a larger than electrical power again and the rotor angle continued to excite.
So we can see it's a periodic drift.
So equal area criteria therefore, can tell us clearly whether we are reaching point c and turning down and this is the first swing.
So first swing the first point where rotor angle after increasing starts to decrease again.
Equal area criterion can tell us strictly speaking only that.
Whether following the fault we will reach the maximum rotor angle and then whether this rotor angle will start to decrease.
What will happen after point c, clearly we see we go down.
Now the next oscillation the next swing could be with the lower magnitude but it could as well be with a larger magnitude that doesn't depend anymore on the behaviour during the first swing that depends on tuning of system controllers.
So equal area criteria does not guarantee global system transit ability, it does tell us only what happens during the first swing.
Once again, if we look these two diagrams these two areas, area one and area two, clearly Illustrated on the diagram with all three characteristic pre-fault, post-fault and during the fault we can see that is absolutely necessary for this two to be equal for the system to be stable or that accelerating area is lower than the decelerating area.
And this is now here verbalised in the slide in front of you.
Now in order to calculate these two areas there is a practical approach because which facilitates mathematical calculation, so instead of equating areas one and two, we do a trick by adding area three to both of them because it's easier to integrate like that rather than...than only partly area two an area one and this is obviously equivalent and this is how the equal area criteria is actually applied in everyday calculations.
Now this integral is easier to solve that's why...that's why we use it in this form.
One thing that we've been discussing until now was that the electrical power during the fault is zero, that is the case only if you have a three phase fault or if the fault is three phase at the generator terminals.
We may have a three phase fault somewhere in the system far away from the generator, so that the voltage generator terminals is not zero.
If the voltage at the generate terminals is not zero that means that some electrical power will still be fed to the system.
So in there if that is the case then the power during the fault red line which was horizontal line at zero level in the previous slide is not any more zero.
During the fourth characteristic becomes also sine-wave as shown in the slide in front of you but it's clearly non zero.
In this case, accelerating area is reduced because a is not anymore the area between PM and zero, it's area between PM and during the fault characteristic.
So clearly the faults which result in non zero voltage of generator terminals are beneficial because the acceleration is in that case reduced.
The other point indicated in this slide is area c which we call stability margin.
So that is the area which is left over if you like.
After all the kinetic energy accumulated during the generator movement through area a has been dissipated while area b was active.
So b plus c should be equal to a.
So the difference between a and b is practically stability margin.
So stability margin the larger stability margin the more stable the system will be or if the stability margin is very large that means to be clear the fault very, very quickly.
Now the next two slides show the derivation of the equal area criteria and this is for your information so we can see that it is reasonably straightforward derivation and the integrals that will be used to calculate the acceleration and deceleration area.
Sow the other thing that we want to talk here it's an example, another example of how this is calculate in case of different fault.
So we'll start with a situation where we have some initial conditions given which are typically power produced by the generator terminal internal voltage of the generator and infinite bus voltage.
The first thing to do in cases like that is clearly to calculate pre-fault operating point.
Pre-fault operating point is calculated by solving a very simple circuit on the previous slide and we can determine what is the initial operating angle, that initial operating angle is calculated to be 25.5 degrees.
The fault is applied and cleared by disconnecting the line.
So the post-fault characteristic is determined and from this post-fault characteristic, we can calculate both new steady-state angle and the limit angle which is essential to determine system stability.
During the fault, it is obviously zero.
By applying equal area criteria we can determine what is the critical angle, what is the angle by which we have to clear the fault to ensure that accelerating area is equal to this decelerating area and that angle is found to be 57.9 degrees.
So the situation we have here is the fault at the beginning of the line.
Fault is cleared by removing the line and then we determine critical clearing angle.
If we look the next example, which is slightly different than the one before, different in two ways.
The first is that initial operating conditions are not the same, are not given in the same way.
So instead of having as in previous case, generate electrical power.
Internal generator volatage.
This time we have generated electrical power, generated terminal voltage and this infinite bus voltage.
Now important thing to remember here is that what we are doing when we are calculating equal area, when we are applying equal area criteria, when we are calculating transistability, is to calculate the power transfer between internal generator voltage, and a given voltage in the system.
So this is not about the power transfer between generator terminal voltage and allocation in the system.
It is always between internal voltage of the generator and the rest of the system.
So the first thing to do here is to determine what is the internal voltage and what is the internal operating, steady-state operating angle of the generator.
Once again this is the angle between the terminal voltage and the internal voltage.
That's why we need to calculate internal voltage of the generator.
So by doing very simple mathematical calculation of this...
solving these second questions which are straight forward, we can find now that initial angle is 28.44 degrees to a very singular as before.
The other characteristic of this example is that the forth now is not cleared by this connecting the line.
So forth happen at some other line which is not affecting the power transfer before and after the fault.
So we have a situation with pre-fault and post-fault conditions are the same.
So limit angle now is not the angle on the post-fault characteristic, which is different in pre-fault, is the angle on the pre-fault characteristic because these two are the same.
In this case obviously, because the line has not been disconnected, power transfer after the fault will be the same as the power transfer before the fault.
In the previous case, power transfer after the fault was reduced because one of the lines was disconnected.
So potential decelerating area was more because the magnitude of the post-fault characteristic was below, was smaller than the magnitude in the pre-fault characteristic.
In this case, the magnitude of the post-fault characteristic and the pre-fault characteristic are the same because these two characteristics are the same So thinking in physical terms, so what does this mean before I actually calculating anything? We know that in this particular case, we will have greater ability to decelerate the rotor after the fault because the post-fault power transfer, which results actually in dumping power, will a larger than the previous case.
If that is the case, one could deduce that we could allow fault to last longer, because we have more dumping power after the fault.
If we could allow fault to last longer, that would mean that our calculated angle in this particular case, should be larger than the previous case.
And if we proceed with the calculation, we can find out that this angle now is 81.7 degrees.
Now which is obviously larger than the previous case, where the angle 58 or thereabouts degrees.
So in the first example, it was 57.9, in the second example 88...81.78.
Clearly, we have better or more stable system in the second case.
Now this also can help with understanding the method for improving the transistability.
What we have seen here is that the fact that after the fault, impedance was equal as before the fault, or in other words, it was not reduced by disconnecting the line.
We have improved transistability.
Improved transistability because we could allow the system, the fault to last longer, or in other words, if we have cleared the fault at the same value of the angle, 57.9 degrees, we even have substantial stability merging, because we have...we would have unused decelerating area.
So the contribution to system stability, transistability here, came from the fact that post-fault characteristic was the same as pre-fault characteristic, or in other words, post-fault impedance, was lower than in the previous case when it was increased by disconnecting the line.
So one clearly, one of the measures for improving transistability therefore, would be to make sure that post-fault characteristics of the system is as low as possible.
So how can we achieve that? Whatever method that you can think of that would result in post-fault characteristic, impedance being...post-fault impedance being as low as possible, that would improve transistability.
So one way of doing that, for example, is connecting series capacitor.
So if we inject very quickly, series capacitor, after the fault has been cleared, then the post-fault characteristic will have impedance, which is lower and this search area will be increasing, and we would have stabilised the system better.
Or if we can clear the fault without disconnecting the line, again impedance after the fault will be larger than even the line is disconnected.
So we would improve transistability.
So one ways of improving transistability is to ensure therefore that the post-fault characteristic, post-fault impedance of the system is as low as possible.
 
Critical Clearing Time, automated transcript 018-10-12 ---  
LECTURER: 
Now this brings us to the question of clearing time or clearing angle.
Now what we've done so far is calculating critical clearing angle, which is the inclination of the rotor calculated in radians or degrees it doesn't really matter.
But it would require calculating rotor angle or measuring rotor angle, Which is not something that we do in real life.
because in systems, as I said before, when we develop generator equations we started by developing them as the people who are working like the machines area would do by writing equations for voltage and then derivatives of fluxes and the model at the end ended up being a set of equations where we had flux, derivatives of flux.
Now this is not something that people working in the area of power system are used to.
They're used to voltage and current.
So, that's why we had to modify the model of electrical machine and to present it in terms of the derivatives of voltages and currents and time constants and so on and so forth.
Similarly, we are not measuring angles in power systems.
We are measuring time, we're measuring voltages, currents, powers.
So, coming up with the conclusion that critical clearing angle is 50 degrees or 70 degrees or 80 degrees is not really helpful.
What we need to know when to clear the fault.
When to clear the fault in terms of time after the fault happened.
So, therefore this concept of critical clearing angle had to be converted into time if possible.
Now, yes, of course it is possible.
By solving swing equation, by integrating twice swing equation and doing some mathematical transformations, we can come up with the time, the time that we can allow to pass within the fault occurrence and fault clearing so that system is stabilised or does the fault is cleared at the time of fault clearing angle calculated previously.
This is clearly shown by the equation in the red rectangle.
So, we can see that fault clearing time or clearing time Delta T.
So, once again, this Delta T is the time for which we can allow fault to be present in the system.
So, the time starts to be measured at the instant of fault and we let fault go for a certain period of time.
During that period time, the rotor accelerates and rotor angle increases from Delta nought to Delta critical.
And at that point we disconnect the fault.
So, Delta critical, Delta T is the time that passes between the application of fault and fault clearance.
And you can see there are two forms of that equation here.
The one on the left is where all the quantities are given in per unit.
So, age in seconds.
Delta critical, Delta, Delta critical is in radians.
Powers are given in per unit.
And Omega nought is also is two Pi F.
If we converted, modified slightly is this equation so that angles are actually given in degrees as we calculate them normally, then the form of the equation becomes slightly different.
So, we have this 18,000 appearing in the denominator of the expression of the formula because that takes care of angles being expressed in degrees and everything else is natural units that are normally using to calculate angles and powers and voltage and so on.
From this equation also, what we can see is that PM minus PE is accelerating power and it's very easy to say that accelerating power in case of three-phase fault generator terminals will be equal to PM because PE would be zero.
In case of electrical power not being zero during the fault in case that electrical power follows the sine wave or sine curve, then the question is what is actual accelerating power? Because it's not a constant value.
It’s the value which changes with time.
So, in that case, what we do typically for calculating accelerating power PM minus P becomes a function of time.
But instead of going to integrate it across the period of time, we just use the average value between starting and end points.
So, PM minus P or the acceleration during the fault is calculated as the average acceleration during the duration of the fault.
So, this slide shows the deceleration of the fault clearing time once again with all steps involved for your information and this conversion at the bottom from values in per unit to values in degrees and seconds.
The final example you're going to do in this set of example is the one where we actually do not have fault characteristic equal to zero.
As I already said, if the fault is at generator terminals if it's a three-phase fault close the generator, then the voltage generator will be zero so electrical power delivered during the fault is zero.
If the fault, however, maybe three-phase still is somewhere in the system, but there is still possibility to transfer power during the fault, then during the fault characteristic will not be zero.
So, the other thing that is important to remember here is that this fact that we can transfer some power during the fault means that the acceleration will not be PM mechanic, equal to mechanical power during the fault.
The acceleration will be lower because the accelerating power is PM minus PE.
If PE during the fault is not zero, then the acceleration is lower.
So, method for improvement of transient stability therefore, would be any method that would ensure that during the fault we have electrical power which is non zero.
That is typically done by connecting breaking resistors or inductors of generator terminals where during the fault generator continues to supply some power to these resistors basically dissipating burning, if you like, the power through losses in the resistors.
However, since there is a possibility of sending some power to something, to some load, we have PE which is non zero therefore the generator accelerates less.
So, these resistors are typically connected immediately as the fault is observed and then removed following the fault disconnection, which is a similar approach as with reducing post-fault impedance that I mentioned before by injecting the series capacitor at the moment of clearing fault and removing it a few seconds later.
So, these are kind of corrective control measures that can be applied to ensure that some parameters of the system are altered in a relevant time frame during or immediately after the fault to improve transient stability.
So, let's look at this example now.
Now again this example compared to previous two is different in two ways.
The first one is the location of the fault, which is now in the middle of one of the two lines, or the bus which is between buses one and two that we had in the previous case and in initial operating conditions.
Now in this case, initial operating conditions are given by power and voltage delivered to the infinite bus system.
So, we don't know anything about the generator.
In the example one, we had power delivered by the generator internal voltage of the generator and the infinite bus voltage.
In example two, we had the power delivered by the generator terminal voltage and the infinite bus voltage.
And now we have power and voltage at the infinite bus site.
So, we have to apply and again some circuit analysis to work out initial operating condition of the generator which is determined by its initial internal voltage and the angle of the voltage.
And that can be calculated following these few simple steps and solving very simple electric circuit.
And we can work out what is the fault, what is the value before the fault.
After the fault, the fault is cleared by disconnecting a faulted line.
So, we are falling again to only one line in service because the faulted line is disconnected and the post-fault characteristic has a maximum value which is again lower than the pre-fault characteristic because the fault impedance changed.
The question is what happened during the fault? Now during the fault, remember in all previous two cases, in the previous two cases, during the fault, power was zero because the voltage generator terminal was zero.
In this case, when the fault happens, the midpoint of the line shown here where the red arrow is, that value drops to zero.
So, in the previous case, generator terminal voltage dropped to zero so we couldn't feed any power to the rest of the system.
In this case, some power will continue to flow from the generator to infinite bus via purple impedance at the top via impedance j02 which is the second line or the third line, depends how you look at it, which was not affected.
Now we have clearly the situation where some power is transferred during the fault.
So, in order to solve this problem, to calculate what that value is, we have to calculate, you know, Thevenin equivalent circuit as seen from the generator so that we can determine what was the impedance and Thevenin impedance and Thevenin voltage at the point of fault so that we can work out the power transfer during the fault.
So, by applying Thevenin’s approach and calculating impedance and voltage, we can work out what is the power during the fault? And you can see that we have a value which is now non zero.
This is clearly a sine wave P during the fault is 0.9152 Sine Delta.
So, we do have a power transfer during the fault.
When we plot this, we will see that this is result in, that this resulted in reduction of deceleration area.
The other way of dealing with this problem is to do star conversion.
Instead of calculating Thevenin equivalent, we can convert three impedances that we have two blue and the purple one on the top left hand side corner we can do, we can apply Delta Star conversion so that we can calculate the equivalent impedance between two locations, if you forgot how to use Thevenin equivalence so that both of these will lead to same result because in both cases we are actually trying to find out what is the impedance between voltage E and voltage V infinity because this is the impedance that determines the power transfer during the fault.
Either applying Delta-Y transformation or using Thevenin equivalence, we will come up to the same conclusion.
The numbers involved will be different initially for impedances, but the final result will be absolutely the same.
So, now with power during the fault being non zero, we have three characteristics.
We have pre-fault, post-fault and characteristic during the fault.
Clearly, existence of during the fault characteristic, as I mentioned before, reduces the acceleration area and clearly we can expect that in this case, we can allow the fault to last even longer.
If we perform this calculation as before using equal area criterion, now equating areas A1 and A2, and A1 is not rectangular anymore, we can find out the critical clearing angle now increased further and became 113.5 degrees, which is larger than in both previous cases.
We had remember we had 79 oh 57.9 and then we had 87 point something and now we have 113.5.
So, the angle is increased further, which means transient stability in this case is even better.
And this is, again, coming back to discussion as before, the way of improving transient stability is to make sure that during the fault, electrical power is non zero.
 
Influence on Transient Stability, automated transcript 018-10-12 ---  
LECTURER: 
So we have discussed in previous few tens of minutes, how we can calculate and determine transient stability using a simple incredible cotillion, and why different configurations of the system, different folds, different locations affect transient stability differently.
In doing so, we also mentioned ways that can help to improve, or help improve transient stability.
I mentioned that the fact that a beneficial for transient stability is certainly, is if the cost for the impedance is as low as possible, and if during the fault electrical power is as high as possible.
And anything that we can do to improve this two would be counted as a transient stability improvement measure.
So let's look now in what is in the affects the transient stability we will use to illustrate each of these in the subsequent slides.
So influences the transient stability includes obviously generator loading, generator excitation, generator parameters, fault location, type of fault, fault clearing time, and post-fault transmission system impedance as already mentioned.
I'll now tell, a few words about each of those, and then I will show you a relevance slides which are illustrating that.
So generator loading, remember generator loading is determined by initial operating points which is intersection between the mechanical characteristics, BM and electrical characteristic of the generator or the characteristic, power generated characteristic that defines how much power generator can determine.
The intersection of these two is given by is, is happening at angle Delta note.
The higher the loading of the generator, is the generator it's a higher output power.
Then PM would cross, or would intersect with PE at a higher value of the angle.
So the value of PM will be a larger at the operating point, the initial operating point.
Therefore if the fault happens then PM being a larger, means that the acceleration of the generator will be higher.
So the kinetic energy accumulated during the fault will be larger, and we would have more problems in dissipating it afterwards.
So what is good for us is to have a mechanical power or initial operating point of the generator, to be at a lower loading, that clearly is not always possible because if the generator is operating at lower output, it's not very economically beneficial.
And clearly it's not making enough money for those who are running the generator.
So they would like to operate generator at higher power as possible.
Generator excitation, is another very important parameter, because if you think about what excitation does, I already said one of the principal roles of the excitation system is to help improve transient stability.
And how this transient stability can be improved.
It can be improved by making one of the components of the swing equation, either bigger or smaller, depending from which angle of we're looking at it, as it is given by one over two HPM minus P.
So the excitation system role, comes into electrical power part.
Electrical power PE, is E times V over X sign Delta.
Where E is internal motivator Generator, V is the voltage at the point in the system where we are transferring the power, X is the impedance between the two voltages, and sign Delta is the sign of the angular difference between two voltages.
So if we have excitation system, what the excitation, what the AVR actually does, AVR, immediately after the fall, boosts internal voltage of the generator.
So once the fault is sense the generator knows, the voltage drops, remember from the discussion of the role of excitation system, and the diagram that shows the generic composition of excitation system.
So once we identify that the terminal voltage drop below a set value, the signal was sent to increase the terminal voltage if the AVR is fast enough.
And we want it to be fast, so that the voltage can decrease as fast as possible, the AVR will increase the excitation voltage very quickly to a maximum allowed value.
Typically two, two to three times of the, of the rated value, for a very short period of time obviously.
So if the E is increased very fast, once the fault happened, then E, V over X signed Delta, electrical power will become higher, so the acceleration will be reduced.
So by having fast acting AVR, which can very quickly boost internal voltage of the generator, we are actually increasing electrical power during the fault, and after the fault, because even when the fault is cleared, the electrical power will be at the level determined by the excitation voltage.
So by boosting the extension of voltage of the generator, we are increasing electrical power, therefore reducing the acceleration, and improving deceleration after the full clearance of the generator.
So this is clearly beneficial for specific transient stability.
Generator parameters X and age, So again, in the spring equation, which is once again Delta Omega Delta T equals one over T, H, PM minus PE.
So if age is smaller, the acceleration will be higher because age appears in the denominator of that equation.
With very large age acceleration is smaller, which is clearly a physically understandable if the generator is a lighter, and disturbance will result in faster increase of the rotation of the generator of the rotor, if the rotor is heavier, if the inertia is higher, then it will be much more difficult to accelerate it.
Therefore, the acceleration will be lower.
Similarly, if a generator parameters, if generator reactants X is smaller, then in electrical power expression EV over X sign delta, smaller x will result in higher magnitude of electrical power, meaning that more power can be transferred through the system, after the fault.
So the generators with lower X would be beneficial, or any action that can contribute to reducing X, would be beneficial.
We'll discuss that in case of a reducing post fault transmission system impedance.
Fault location, another measure, another influence of transient stability.
If the fault is at generator terminals, the terminal voltage to the generator will clearly.
Drop down to 0 as we saw in two examples that we had earlier.
And the electrical power delivered to the system will be 0.
Therefore, the acceleration will be the full mechanical power.
If the fault is somewhere in the system, as in example three, so that the fault, the voltage (INAUDIBLE) during the fault doesn't drop to 0.
Some electrical power would be able to be transmitted through the system during the fault.
Therefore, the acceleration of the system will be lower.
Same applied to type of fault.
Three-phase fault will drop all voltages down to 0.
Other types of fault single line to ground or two line to ground fault or line to line fault will only result in either one or two phases being able to continue to transmit power during the fault.
Therefore, electrical power during the fault will not be 0.
And the system will accelerate less.
The effect of fault clearing time is reflecting the fact that if we cleared the fault sooner.
The acceleration of the generator will be lower because we are accelerating it for a less time.
If we wait too long to clear the fault, we will give a lot of time to generator to accelerate.
And then, it would be much more difficult to dissipate or disaccumulate the kinetic energy.
And finally, post-fault transmission system impedance.
We already saw that in examples shown previously that if the post-fault impedance is high.
Then, the ability to decelerate the rotor is reduced because the magnitude of the post-fault characteristic is lower than or very low.
And certainly lower than pre-fault characteristic.
If we keep the post fault impedance of the system low then more power can be transferred to the system after the fault.
And clearly the generator can be decelerated much more efficiently.
The model, as I said, now we can go to how do we do that.
How do we do this analysis in real world? We do not clearly, we do not use equal area criterion.
Because equal area criterion is strictly applicable to single machine (INAUDIBLE) bus system.
There are some generalising equal area criterions which can be applied to multi-machine systems.
But they are not as universally applied for very large systems as the conventional numerical integration.
So, what we do we have a full model of the system non-linear differential equations.
And then, applying some of the numerical integration methods.
We calculate rotor angles after the fault, observe oscillations and base on that we determine whether oscillations are damping or increasing in magnitude over this periodic swing.
So, it's not discussion of actually accelerating and decelerating powers.
Purely, looking at the responses.
Now, I already mentioned that this essential requirements is how much detail, what period of interest and how quickly we should find these results.
Considering that in this type of models, we are using non-linear systems and that the faults in the system can be different.
Symmetrical or asymmetrical.
We have to apply to certain extent symmetrical components to calculate faults during propagation of power and network equivalence for asymmetrical faults involving earth.
Or clear asymmetrical faults when we have line to line fault.
Also transformer winding connections then become very important.
Because as I said before, transformer winding connection will affect the power transfer in 0 sequence component.
Control limits are important.
That's why the non-linearity is here very very important.
Compared to small disturbance stability where non-linearity was not considered.
As we were dealing with only small disturbances around the operating point.
Now, control limits will clearly prevent controllers to exhort action beyond certain limit.
So, in synchronous machine model.
This is just simply clarification of some of the values that we have to put in the model.
And that you are aware of when we are entering values for excitation voltage and for exciter output current.
So, these are given here on the right hand side.
You can clearly see that voltage as we calculate from steady state.
Which is Ef, the capital E on the right hand side of the equation.
This is something we get from solving the simple circuit equation as in previous examples.
The voltage that we actually use in numerical calculations in the software is not that value.
It's slightly different value.
Which is calculated as the ratio between resistance and reactance of the generator.
Multiplying that value.
And it gives the value which is actually entered in the equations.
When the numerical integration is applied.
This is the trick...
..this is how it's done, this is how it should be done.
But again, fortunately this is not something that we should be worried or you should be worried these days.
As these are standard procedures built in commercial packages.
So, you don't need to worry about this, this is all done in the background.
I am showing this to you in case that for some reason you want to program it yourself.
That you are aware that initial value for either of these should be value calculated like this.
And it's typically very very small.
0 to 0 something.
Because resistance, Rfd is the resistance of the field winding.
Is very very small value.
And Lad unsaturated is the unsaturated magnetising reactance in de-axis.
Or armature reactance in de-axis, the value which is of about 1.5 to 2.
So, when you divide per unit value of fault resistance with the value which is above 1.
And multiply it by Efd, which is typically above 1.5 1.6.
You will get that Efd is a very very small value.
Again, this is not something that you should be worried about.
As this is done automatically for you by existing software packages.
What you are going to do now is to discuss something which is more than equal area criterion.
Or you can say it's advanced equal area criterion.
As in this case, we are studying the system stability during non-symmetrical fault.
Now, non-symmetrical fault will be a single phase, two phase, two phase to ground.
And there is a trick.
Or a mathematical approach, how this problem is addressed.
Clearly, we first calculate as usual normal circuit values for pre-fault and post-fault operating condition.
But the thing is how do we deal with the situation during the fault.
During the fault, situation is solved in a way that fault impedance is inserted, delta XF here as you can see in the bottom line.
Of figures on the left.
This delta Xf is not actually the physical resistance or whatever impedance between the fault and the earth.
Or between two faulted locations, two faulted points in the system.
This is mathematical term.
Which is used to represent different types of faults.
And reflect that fault in the system may not always be symmetrical.
And this delta Xf should be added in addition to actually resistance of the fault if that is specified.
Usually it's not, usually it's assumed that fault impedance is.
The actual fault impedance is 0.
And then, delta Xf is purely mathematical addition or trick if you want to represent different types of faults.
And that, delta Xf has different value depending on which type of fault we want to simulate.
In case of three phase fault, it's 0.
And in case of single phase to ground fault for example.
Is the sum of zero sequence.
And negative sequence impedance.
And that's why we need to know negative sequence values and zero sequence values for system components.
And we need to know transformer winding connections.
Because transformer winding connections will affect the shape of zero sequence network.
So, we have to calculate all these values.
In order to find out the Xf.
Then, going back to previous slide.
Putting delta Xf here.
And we have a wide connected impedances between voltages.
Between voltage E and voltage V.
And as I said, the application of equal area criterion requires finding the power transfer between E and V.
If this was the fault, clearly some fault current will go.
And some power will be dissipated through delta Xf.
But some will continue to flow between E and V during the fault.
That's why what we need to do is to do Y delta conversion in this case.
To find the path, a clear path between E and V.
And in this case we do not need to calculate other two impedances shown here on the slide in parallel with two voltages in the left and the right.
With voltage E and voltage V.
Because we are only interested in power transfer between E and V.
And impedances within these two points.
So, this X is calculated between E and V would be the X that goes in electrical power expression.
EV over X sin delta.
So, that X in power expression will be in this case Xdf prime.
So, with this power transfer, as you can see, we have post-fault characteristic.
Which is different from pre-fault and during the fault characteristic which is different from pre-fault and post-fault.
And then, calculation of equal area criterion is straightforward after that.
And we can find obviously what is the critical clearing angle.
Example of the influence of type and distance of fault.
You can see here, as I said when discussing what influence transient stability, I will use (INAUDIBLE) So these are the slides I mentioned before.
So, on the left, we have effective influence of fault type for a three phase fault.
The power transferred during the fault is 0.
For line to ground fault is the largest part transferred during the fault.
Because obviously we are transferring power through healthy lines.
Therefore, during the fault characteristic has the largest magnitude.
Other two faults are somewhere in between.
On the right hand side, is influence of the distance of the fault.
The closer the fault is to the generator.
The more severe the situation is.
Because if double fault (INAUDIBLE) voltage is 0.
If the fault is further away, voltage of (INAUDIBLE) terminals is non-zero.
So, some power can be transferred.
And that obviously helps reducing deceleration.
I discussed already pre-fault.
Effect of the pre-fault loads.
So, this is just illustration of that.
You can look at that by yourself.
Example of generator loading again illustrated to a recorded responses.
The more load generated for the fault is the larger the oscillations are.
And the influence of stability margin.
This is direct reflection of how soon the fault is cleared.
If the fault is cleared for a very brief very quickly after its inception.
The generator will accelerate less.
And therefore, there will be larger stability margin.
If the fault is let last longer, stability margin maybe non-existing.
Which will be the critical case when acceleration area A is equal deceleration area B.
So, we have zero stability margin.
And this is illustrated here in these two slides.
The top one shows small.
And the bottom one shows a large stability margin.
So, what you can see that in case of small stability margin.
We have first bigger oscillations.
And possibility of having superimposed oscillations.
So, if you look the top diagram it's clear that during first two cycles.
We have two modes participating in these oscillations.
Because there are two superimposed frequencies on this slide.
And then, clearly after the first two cycles the better damped oscillation which is superimposed on the peaks of these two swings disappears.
It's completely damped and the system continues to oscillate with a less damped oscillation.
Which means is that in case of lower stability margin it is more likely that we will have many oscillations present in the system.
And that the system response when plotted will be less sinusoidal.
This is not that general.
But I said is more likely.
In case of higher stability margin, it is more likely that you have a clear sine wave oscillation govern, dominated, by a single mode.
Influence of auto re-closing.
You have heard that in some cases we have a possibility of attempting to re-close the system.
Even though during the fault line maybe disconnected for a certain period of time.
And then, attempt is made to close the faulted line.
If that fault has been cleared in the mean time.
The line will be successfully re-closed.
And then, our post-fault characteristic changes.
Because we are jumping here as you can see from post-fault characteristic.
Which is blue to pre-fault characteristic green.
So, the deceleration area automatically increases as well as the stability margin.
So, this is clearly beneficial to the system.
Now, automatic re-closing is attempted twice.
And after second attempt, the fault has not been cleared then the line is permanently, permanently disconnected.
This automatic re-closing is introduced clearly because of these reasons.
As if the fault was very short lasting for whatever reason it may have been.
We do not actually need to disconnect the line.
We can continue reconnect the line and continue with a higher power transfer after the fault.
The influence of AVR I only mentioned that while the AVR when the fault happen the AVR detects that the voltage at the junction is reduced and starts boosting the voltage.
This boost of the voltage results in familiar characteristics as shown in the right hand side part of the slide.
Family of during the fault and post fault characteristics which are increasing as the time is passing by.
So we're actually jumping from one characteristic to the other as the AVR is reacting.
And there is a consequence of that.
We can clearly see that first the acceleration area is reducing I will say a little bit.
But at the moment the fault clearing e internal voltage or generator is so much increased that the post fault characteristic is not anymore the same one that we have before the fault.
Because e is increased, the overall post - fault characteristic goes up and it might increase significantly.
So AVR not only reduces acceleration but more importantly significantly increases deceleration area.
And in such way helps with stability.
Similar thing here is illustrated for governor.
I said they're not considering governor in many of these studies.
In most of them we do not consider the governor would do anything because they're prevented from acting very quickly.
And once their action starts, we already have AVR reacting and fault being cleared and typically fastening is ensured.
I already mentioned that governors tend to have negative effect on oscillation.
They may result then in reduced dumping of sustained oscillations after the fault.
However, the action of governor if they are fast enough would be in reducing mechanical power.
So once we sense that the generator is increasing the action of the governor would be to close the valves to reduce valves that are controlling the input of work in fluid - gas, steam, water into generator.
So the action of governor will be to close the valve therefore reducing mechanical power.
Reduction of mechanical power results in drop of mechanical characteristic.
So it's not horizontal line anymore.
It's a line that goes down.
So because of that if you look on the slide, you will see again same as in case of AVR reduction in acceleration area and increase in this deceleration area.
Even though the governor may act fast, we're talking here of the accelerating area lasting summary in the space between three and typically six cycles.
So a 50 hertz system three cycles is 60 milliseconds and five cycles are 120 milliseconds.
So this is the typical duration of the fault at high voltage level.
So even with a very fast acting governors, it's not likely that governors will be able to substantially reduce the mechanical power during 120 milliseconds or 150 milliseconds.
So the effect of governor theoretically would be in this way a reduction of accelerating area.
But it is more likely that the fun effect of sounds it would be more in the increase of deceleration area.
As you can see the drop in mechanical electricity results in this purple enlargement of decelerating area and therefore helping with overall system transmissibility.
The same thing is illustrated in this slides we'll skip that.
Now the question of faults in a large system.
So because the system with many many many generators can have faults at very different locations.
And the question which generator will first lose synchronism is not really very straightforward one.
And it will depend on many reasons.
It will depend on severity of the fault, on the location of the fault, on the size of individual generators which accelerates faster, which accelerates slower.
It will result in also this connection in fault happens some lines with maybe may end up being disconnection of the fault of the faulty line there resulting in change powerflows which will affect other generator.
So they need be series of cascading events happening in a very very short period of time.
So it is a very difficult to say which generator will lose synchronism first.
The generator or generators nearest to the fault typically lose synchronism first because in their case the acceleration is the largest.
Once they lose synchronism that endangers the balance in the whole system.
So some other generators can stop falling in a cascade.
And this is example how the systems synchronism can be lost in a system with the this is example with several generators.
There are four actually shown.
Depending where the fault is, different generators exhibit different behaviour for different faults.
So different location of the faults in the same system.
And you can see how generators may react to these different faults.
So if we just look at top left corner and bottom right corner, we can see that for the fault in which is closed generator one generator one lost synchronism immediately while other three illustrated generators, generators two, three and four don't appear to have lost synchronism at least not for first two seconds.
They continue to oscillate pretty much in synchronism.
And the oscillations are not very if you like wild.
On the other hand, fault which is closed generator four did not result in this case in generator four losing synchronism as was the case in generator one and fault close to generator one.
In this case, fault close the generator four resulted in a periodic drift of generator two and lose of synchronism generator two while other three generators oscillate some very violently like generator three.
Some with a lot of modes involved.
A lot of trembling.
Generator one you can see the oscillation generator one is not clearly sideway.
It's very distorted siren.
But they're not losing synchronism.
And if you compare these two, if you like dynamic signatures of the system, they're quite different even though they pre fault operating condition was the same, generates are the same, topology was the same.
The only difference was the allocation of the fault.
And this is a sequence of events that may be resulting from the action of the protection.
So with this we came to the end with discussing small and large or transient stability.
And what is left now to look into ways of improving power system stability.
 
Intro to Enhancement of Power System Stability, automated transcript 018-10-12 ---  
LECTURER: 
Hello, again.
This is the final chapter of lectures on Power System Dynamics which will deal with the enhancement of power system stability.
So far in this block of sections, we dealt with basic definitions of power system stability, introduction of power system dynamics, modelling of different network components, generators, lines, transformers, loads, small disturbance stability analysis in small and large systems, transient stability analysis in small and large systems.
And that brings us to this final chapter which deals with the methods for improving power system stability both through control actions and through some corrective control measures.
So this last chapter will, therefore discusses the way, how we can apply some of the techniques we talked about in this chapter on small disturbance stability.
And some of the techniques that we talked about in the chapter on transient system stability.
How can we put them together to improve overall system dynamic behaviour.
So, enhancement of power system stability.
There are ways how we can improve the overall system stability.
The ways which are related to some preventive and corrective measures.
Most of the actions that have been used in the past were related to preventative measures by focusing on doing appropriate control setting, appropriate system configuration, adjustment of protection.
So that in the case of disturbance, the system reacts in a way how we envisaged it will react.
This obviously considered installing actions, installing measures, preventive measures and tuning of controls for assumed system scenarios.
Some of these scenarios may have been very rare scenarios.
So one may think that the investment in designing these preventative control measures might have been a bit excessive.
I'm not saying it was, but we had to presume what the system may experience and then to design appropriate control in advance.
The other approach, which hasn't been very widely used in the past, which may become more important in the future when system behaviour becomes less predictable because of the increased uncertainties in system dynamic behaviour, thanks to integration of less predictable renewable generation and new types of loads.
So in that case, we may not be able or have enough funds to design appropriate control measures in advance for all possible scenarios.
So we may need to result to actions that would take place only after particular disturbance has been determined.
Those would be corrective control actions.
We are going to touch brief on both of these.
But we will start with the conventional way of how the power system is basically improved today.
Basically, whatever measure we have designed and we applied in the past, there is always a balance between what may go wrong and how much money we have or want to invest in preventing systems from becoming unstable.
And there are clearly a range of control options that we can apply to improve system stability.
The most frequently, most widely used one is to apply system controls, namely power system stabilisers at the first place.
Which are applied to excitation systems which is typical application in 99% of the cases probably.
And there is obvious the possibility of applying them to a governor as I already mentioned it in one of the previous sessions where I said that if it was applied in the governor, then there would be decoupling between a voltage and power regulation through excitation control loop.
Therefore, both of these control actions will be enhanced without interfering with each other.
There is, obviously, application of AVRs which as I said, improve transient ability, first thing stability in particular.
There are things like fast valving which is disconnecting a part of steam turbine immediate after, during the fault or immediately after the fault so that mechanical power is reduced.
Possibility of generator tripping which is, yes, it does improve transient ability of the overall system.
But as I said in the beginning of this block of lectures, once we lose a single generator, our system actually became instable because the system with that generator disconnecting will not be the same system as the system they had before.
They may have saved the many, many, many customers from experiencing blackout and limit the impact of losing that one generator to very small area of the system.
But the system in a fact lost the stability in the way of stability of the system that we had before the disturbance.
Now, there are ways of applying braking resistor or shunt or series elements which will be corrective measures.
I mentioned all of those already when discussing transient ability.
Because braking resistors would help with dissipating some power from the generator during the fault.
And hence increase electrical power, reduce accelerating power and decrease accelerating area during the fault with reference to equal area criterion.
Injection of shunt or series elements will affect the system voltage.
So affecting the system voltage would again result in increase of electrical power because system voltage, as you may remember, appears in expression for electrical power.
Once again, E times V over X sine delta.
So, inserting shunt or series elements would result in V, in that equation going up.
So, if V goes up, then the magnitude of electrical power goes up.
Therefore, PM minus P becomes smaller.
So the system accelerates less.
 
Improving Small-Disturbance Stability, automated transcript 018-10-12 ---  
LECTURER: 
So the first thing that we're going to talk about now, going through this list is the design of system controls.
And this is the traditionally most widely and frequently used method for improving a system stability.
Before going into actual design of damping controls, I want to refresh your memory or to reiterate once again, what is the role of excitation system in general.
So one thing with excitation system is to make sure that the voltages are maintained at desirable level.
And that's during transient disturbance.
We improve transient stability first.
And then if we're at PSS of that system to improve subsequent oscillations, damping of subsequent oscillation.
So AVR improves voltage control and transient stability.
But under certain circumstances, in particular or have a generator loading in heavy power transmitting line, fast acting, low time constant more than AVRs may result in reduced synchronisation talk and introduction of negative damping.
So yes they will help with first swing stability and make sure that the following the initial step is to generate lots of those up and it gonna start s returning back the previous operating point.
However, subsequent oscillations may be either prolonged or may even be with increasing magnitudes.
Therefore we need PSS.
So PSS comes along.
And PSS for sure reduces the subsequent swings.
So reduces the magnitude of the subsequent oscillations.
However, during the initial acceleration of the rotor during the first swing, it may due to interactions with the AVR result in actually in the first swing being higher.
So the allowing the angle to go further up then it would have been the case if the PSS was not present.
So both of these controllers, AVR and PSS when considered independently have positive and less positive I won't say negative and less positive influence.
Once they are put together in operation, the overall benefit of them acting together is positive.
The overall benefit of AVR and PSS is that both voltage regulation is satisfactory.
Transient stability is satisfactory for swing stability in particular.
And subsequent oscillations.
Damping of oscillations after the fault is satisfactory thanks to the PSS.
Now power system stabilisers are introduced for the first time in 1960s basically when application of excitation of first acting exciters resulted in increased oscillations following the initial stabilisation of the first swing.
And they are connected as I would say in the same control loop as the AVR.
The major problem with AVR and PSS acting together is that both demands to control frequency or speed.
And the voltage that it would generate have to be accomplished by adjusting the excitation voltage.
So if you look the block diagram at the bottom of the slide, both signal from PSS and signal from a voltage set point.
So difference within terminal voltage and reference voltage.
So the voltage error that exciter is responsible for.
And the signal from PSS are coming in same summing junction, and then the regulator and the exciter have to act upon this combined information coming from these two devices.
So this is where the major source of interference comes a long.
Now the role of PSS is that in steady stay, when there is no variation in voltage, sorry in speed then delta omega is zero it should not do anything.
It should not interfere with voltage control.
Once the variation in speed appears in the transient state and the voltage oscillate due to (INAUDIBLE) as well, the task of PSS is introduce a signal in phase with speed deviation.
Remember when we talked about this damping component of the electrical torque which is KD times delta omega.
And we said as long as this damping power into use in the system is positive.
This damping power helps electrical power to balance mechanical power.
And therefore minimise the acceleration.
So for damping power to be positive, damping power which is the product damping coefficient kd and speed, deviation delta omega.
For each to be positive we said kd has to be in phase with delta omega.
So the role of PSS - power system stabiliser is to introduce damping signal kd which is in phase with speed deviation.
If that is achieved, then additional damping power will be added to the electrical power and hence total acceleration of the generator will be reduced as pm minus pe plus pd would be lower.
There are power system stabilisers which act upon different input signals.
But whatever the input signal is either speed deviation or electrical power or frequency deviation, we typically have a configuration as shown in this slide.
More typical is the top then the bottom one.
The top one consist basically of three components.
One is the gain.
Then we have high - pass filter which ensures that PSS does not interfere with the system with the speed not...
..without... in steady state where there are no deviation speed.
And the third and fourth component or fifth eventually are lead/lag blocks which actually ensures that injected signal is in phase with speed.
So if you look this structure of the power system stabiliser we can say the following.
The blocks on the right hand side lead/lag blocks, we can have up to three of those.
Because each of them can't provide about 57 degrees shift.
So these blocks on the right are there to position the action whether is going to be in phase or out of phase with speed deviation.
So they are aligning the action of PSS.
The first block KSS is the gain which provides the strength of that action.
How big the interference if like by PSS should be? And the middle block, the washout or high - pass filter here actually limits the action to a certain frequency range.
So likely more complicated system PSS would be if we have another filter which is now low pass filter, this filters are typically applied only if we have concerns that there might be interference with total oscillations.
So this low - pass filter actually ensures that frequency is only lower than certain level pass through typically lower than five hertz because in that case we're cutting off any potential interference with total frequency range which I said before is within five and 50 hertz.
So with these two filters together, high - pass or a washout and low - pass filter we're actually framing the frequency range or creating a frequency window within which the PSS action will occur.
PSS gain will decide how strong that action will be.
And lead/lag blocks are orienting the action, deciding in which way this action will happen, whether it will be in phase with speed or not in phase with speed.
So this illustrated again as I said before the two filters washout and low - pass oscillate in the left and right side are actually reducing or opening the window through which the PSS action occurs.
In reality this is how it looks.
They have a set values because for any system we want to act only on frequencies in the range between above 0.2 and five hertz.
So we have to design filter in such a way that only that range is affecting .
Obvious the filter cannot be designed as a sharp step function in the left and the right that has some spillage on the left and right.
So there's potential interference at slightly here frequencies.
But if we are designing this filters, we're trying to limit their action at about frequency of interest.
Now these the following two slides illustrate how actually, PSS and AVR reacts together and why PSS is helping with damping.
I'm not going to go into detail with this, but what I'm trying to do, what I'm going to do instead, I will explain you in words how this, or why this interaction is happening.
The further details about this you can read in the book by Biolek and Maohuske, power system control stability from which this slide is...
are based on which this slide was developed.
In this particular diagram on the left-hand side you can see delta D, it should be delta-delta, which is direction of the angle.
Now, what actually happens, why PSS and AVR interfere with each other.
So, remember I said when the fall happens, the general 50-meter wall that drops down, the transducer sends the voltage reduction, they send the signal to AVR, please... They don't say please obviously, signal to increase the... to boost the extension voltage of the generator so that the terminal voltage can be corrected.
So, this will go and say increase the voltage and keep it up as much as possible for as long as possible, because the longer this voltage stays at the ceiling, the greater electrical power will be, EV over XM, delta will be higher because E is part of it.
So, if they boost E to a high value, PE will be bigger, so, PM minus PE will be smaller, so, the generator will be accelerate less.
So, the demand from AVR is to increase E, to keep it at the ceiling as much and as long as possible.
On the other hand, PSS who is monitoring the speed deviation, PSS notice that speed started to change, it goes up and down, up and down, up and down, so, increasing and decreasing.
So delta omega, the variation in speeds is ultimately positive and negative.
So, the role of PSS as I mentioned before, is to inject the signal which is in face with speed deviation.
Therefore, PSS demand would be to alter excitation in such a way that the injected signal is always in phases with speed.
So, since the sign of the speed changes, the sign of the signal that PSS has to inject would change.
The four PSS design would be increase excitation, reduce excitation, increase excitation, reduce excitation.
This is the only work PSS can do because it acts through a same control loop as AVR.
So, when you think about these two requests AVR wants E to go up and to stay up as long as possible continuously.
PSS on other hand requires part of the cliff for it to drop down in order to control the oscillations.
So, that as a consequence results in E being brought down from the ceiling few times during the first cycle which is something that AVR won't like, because E is being brought down from the ceiling, electrical power would not stay constantly high, so, the machine will accelerate slightly more.
Therefore, with PSS supplied, we will have first swing magnitude, angle mantle slightly higher.
However, as this first thing is gone, the continuous action of PSS will ensure that the oscillations are damp.
This slide and the following slide actually show how the application of PSS effectively rotates the action, the damping signal, damping talk produced by the excitation so that it design, it generates a signal which in phase with speed variation.
In the previous slide, if you go back to previous slide, and you look the green bottom vector which is deltas E prime as a function of delta EF is acting towards right-hand side corner of the slide, and you can see that the negative dumping which is a horizontal component of that vector who is actually introducing negative dumping, it acts in opposite direction than the variational speed.
When we apply PSS, what happens, that triangle that is green triangle goes on the left, and then that component appears on the left-hand-side in phase with the speed so PSS actually helps improving damping of the system.
This is exactly what they explain, but this is now showing through physical diagram.
As I said more about this can be read in Biolek Mahouske book.
The application of PSS has been successful, is successful however, there are obviously some limitations because we have more than one generator in the system, and PSS is installed in one generator may be effective in damping of oscillations of that one, but may not be as effective in damping a global oscillation system.
So, for coming up with a global optimal solution, PSS would have power stabilisers have to be designed in a coordinated manner.
There are different ways of doing that, one is sequential tuning of PSS's when you tune one by one, assuming the previous one is tuned properly, then you have a second one, a third one and so on.
The problem with this sequential design that every next, every subsequently tuned PSS relies on previously tuned PSS's.
So, if one of the previously tuned fails to operate, then all of those who are designed after that one will not be as efficient as before, because they are assumption loss of the previous PSS's already in the system.
This is the way tuning, sequential tuning is most widely used, it has been shown to be effective in many many many cases, in a vast majority of cases, but this is said, it has this weak link which is that if the previous within PSS's fails, everything else could collapse afterwards.
The other way is the coordinate tuning of PSS's which is through an optimization programme, where you consider all oscillations in the system, and then you design a control system in such a way that you place PSS's at appropriate generators, and adjust their setting in such a way that all oscillations of interest in the systems are adequately damped.
This is complex optimization problem, and typically not performed by system operators, because of the lack of resources, and not only resources but quite often resource in terms of human resources, but often the main reason is the lack of software to do that because commercial standard, commercial suffer back at this and do not make provision for that.
So, if you want to do that for the system then you typically have to higher a consulting company or consultants who can do that for you.
I will discuss the shortcomings of PSS, so, what PSS can do if it's applied together with AVR, and why this shortcoming is not desirable.
Now, we will talk about how we actually design PSS, how we improve system stability through control design.
So, the thing that we have to look at here is our power system is here shown as GFS, transfer function GFS, and our control whether it's a power system stabiliser, or either damp any other damping controller is monitoring deviation of system variable in this case either changes speed, frequency, or electrical power, does something with it, and then injects controlling signal back into the system.
Now, this action is basically based on the fact that change in eigenvalue is proportional...
change in eigenvalue of the closed loop function is proportional to the residue and the magnitude of the transfer function of the controller.
Now, this residue corresponds to open loop eigenvalue, and edge of lander I is the magnitude transfer function in the feedback loop.
So, this is another reason why we are calculating residues.
I mentioned in the block which was dealing with small disturbance...
they calculate residues to determine what is the best location to place power single throw, I didn't say then how we then determine that, but the rule of calculating...
..the importance of calculating raises it two fold.
The first one is arising from here, because obviously the shift, the change in eigenvalue will be bigger if the magnitude of residue is bigger.
So if we calculate residues at different locations, the location where the magnitude of the residue is the largest, will be most effective in moving that eigenvalue in the desired direction.
If the controller is installed there and that move will be proportionate to the most of the residue and obviously the gain, clearly the gain of the controller.
So, from all possible locations, if you look the eigenvalue in the left hand side of the complex plain, eigenvalue which is unstable, we can move it in whatever direction we want.
We can move it up, left, right, half left, half right, whatever.
Up to the left, so it's like a, if you like it will be a north western direction or a south western direction whatever.
So we can move within whatever direction we want.
The whole point is to move it as far away from stability limit as possible, so clearly in the direction of the red line.
Note that on this diagram, the vertical axis J omega, and the horizontal axis is damping, is delta not s, is damping of the, of the eigenvalue.
So if we somehow, can make sure that this eigenvalue moves straight to the left, then the design of the control will be the most efficient.
And actually we can do that because that information of movement straight to the left is provided by the angle of the residue, phase angle of the residue.
So residue, same as component of the eigenvector if I mentioned before when I was talking about mode shape.
So the residue is a complex number.
The magnitude of residue tells us which is the location, which of the generators involved in a particular mode are the best location for placing control and the phase angle of that residue, is telling us how much we have to shift the signal through the controller, so that the action is straight to the left.
Or in other words, what phase shift should PSS introduce.
So that it ensures that damping signal is in phase with speed variation.
Options for shifting critical modes are various.
We have, we may have critical modes which are very close to stability limit but on the left hand side, or in the right hand side of the complex plain, meaning unstable so the desire is to shift them from the right, further to the left and beyond some sigma not value which is the minimum damping that we want to have in the system.
Here, sigma is damping and theta down there on the left is damping factor, that I mentioned when I was talking about 5%, 10% damping factor when discussing the location of eigenvalues in complex plain in mouthy machine system at the end of block that dealt with small distability So we may decide to shift eigenvalues straight to the left from the particular damping.
Now, that will improve the damping certainly.
We may decide to shift them just below the critical damping factor value.
So, we may decide that all eigenvalues should be below this 5% line as something worth that we are mostly concerned with.
Because pushing them below particular damping factor also affects the initial overshoot.
When we are talking about improving damping alone, we are not worried about the initial overshoot.
There is a third way, obviously to achieve both ends to shift the eigenvalues to the left in such a way that damping factor is lower or higher than 5% actually.
And the damping is better than some prescribed initial value.
Now, why do we want to do that? Because this graph on the right here inside shows that depending on what damper factor is, we have different overshoot.
So we don't want to be the initial signal to follow after the application of PSS and have very high overshoot because it may affect the controls and damage something.
Some settings in controls, so or result in excessive swings of real and the active power of the generator.
So we have to limit this initial overshoot.
With 5% damping factor, we have overshoot.
So the damping factor of on the horizontal axis you can see that depending on the value of the damping factor we have different overshoots.
So if the damping factor is about 0.7, we have overshoot of about 5% with damping factor 0.5, we have overshoot of about 16%.
Typically we want to have overshoots between five and ten percent in the system response.
So we are talking about damping factor of about 0.5, 0.6 as desirable values.
Now, when we want to do that, to shift eigenvalue in that area, we can keep doing it until we fit it in the shape of the, in the part of the complex plain as described on the left.
And there is away of doing that.
By making sure that the phase shift of the PSS that we are applying is calculated based on this expression.
So, this is the value, how we calculate phase shift of the PSS.
Or in other words, how we are deciding on the led light blocks.
How much angular displacement each of the led light blocks can produce.
So if we find out the difference between 180 and the phase angle of the residue, that gives us what is the required phase shift through power stabiliser.
That calculation is slightly different depending whether PSS is in positive or in negative loop.
PSS is a positive loop is typically one acting with the speed as the input and PSS in negative loop is the one acting with electrical power as the input.
But they ultimately what we are doing, we are rotating the residue if you look at the diagram on the bottom right hand side, we are rotating the residue from where it is originally towards -180 degrees direction.
Considering that one PSS block can typically introduce about 60 degrees phase shift, we may have up to three blocks which will then make sure that PSS is injecting sigma, which will ultimately push the eigenvalue straight to the left.
And there is this, based on this requirement we can calculate different components for real led blocks and this is a formula for genetic formula for PSS.
PSS runs the function.
We have, first there is a number.
WS and FS are washout and low bus filter.
And KPSS is a gain and then one plus the S over one plus alpha TS on power N is the number of led light blocks that we need.
And number of led light blocks is determined by how much phase shift we have to introduce assuming that one led block is for producing phase shift of up to about a radiant of 57 degrees.
So based on that determine how many levels need and then applying the formula below we can work out exactly where the coefficient alpha and time constant should be.
And that will result in PSS acting or moving the eigenvalue in the desired direction.
Now, the process of tuning of PSS is going as follows and we are going to illustrate that on the next example.
The previous two slides are showing, they are just verbalising what I was saying, that we have to do it considering the potential shift per phase and also some over or under compensation depending on how many blocks we have in the system, and to ensure that system is not being over compensated and then actually acting in the wrong direction.
 
Tuning of PS Stabilisers Case Studies, automated transcript 018-10-12 ---  
LECTURER: 
In order to illustrate how this tuning is actually done.
We are going to consider again a very simple system.
Which has a generator operating against infinite bus.
And if that original system is represented by a third order model.
Which is the constant excitation model.
Which has three differential equations.
Two for electromechanical equation, and one for excitation, for field winding.
So, altogether three equations.
Three equations mean I have to repeat this to make sure that you absolutely understand.
So, with three differential equations the state matrix will be 3 by 3.
Therefore, there will be 3 eigenvalues.
And one eletromechanical node.
Because there is only generator in the system.
So, if you look the eigenvalues shown on the left.
We can see three eigenvalues.
And there is one complex conjugate.
One of them is complex conjugate.
Which is the mode of interest.
Obviously, the one with a negative frequency is not relevant.
So, what we have, we have a mode.
Whose real part -0.118.
and imaginary part is 6.18.
This is in radians.
So, 6.18 is about 1 Hertz.
And if you look the figure below it shows the oscillations which last for about 15 or almost 20 seconds.
So, it's poorly poorly damped system.
Now, if we apply an AVR, slow acting AVR.
Which has only one control loop.
One gain, and one time constant.
That AVR is now adding extra differential equation to the system.
So, the overall model now will be 4 by 4.
Therefore, there will be 4 eigenvalues.
And as we can see...
there are 4 eigenvalues.
And the damping of the system actually became worse.
So, we have large oscillations and they are lasting longer.
So, this AVR actually didn't help much.
So, we have to do something else.
Let's try what we can do.
And then transient stability again will not be improved significantly because slow acting AVR will be slow in boosting the voltage.
So, if you apply fast acting AVR, so different setting.
Which is short time constant in high gain, we still have 4 eigenvalues.
But in this case, as you can see, not only that oscillations are worse than they were without AVR.
The oscillations have actually grow.
They grow slowly.
But after 30 seconds they become excessive.
So, system is actually unstable.
Transient stability is improved.
But the system becomes unstable.
So, we have to deal with that.
Eigenvalue, if we look at the previous slide again.
Eigenvalue now became unstable, it moved from the left hand side of complex plane to the right.
The frequency hasn't changed much.
But the system became unstable.
So, we take that eigenvalue because the system is only one.
There is no need to calculate residues for other locations.
We can just calculate residues of the open loop transfer function between the speed of that particular generator and extension voltage.
Which is where the PSS will be placed.
So, calculating residue for that open loop transfer function.
We can determine what is the angle of the residue and gain.
Based on the residue angle we can then determine what should be the phase shift.
So, the calculated phase shift in this case is -136.1599, for whatever point 16, degrees.
So, we need shift in -136 degrees direction.
So, this is how much the PSS should introduce.
Because one block can introduce is only 57 degrees.
This requires to have 3 lead-lag blocks.
Applying formulae from the previous slide we can calculate parameters of each of these blocks.
And they are shown below.
So, we have a PSS now.
Which has a gain component and three lead-lag blocks.
The lead-lag blocks, lead-lag blocks applied guarantee that the move of the eigenvalue will be in the designed direction.
Which means straight to the left.
But we haven't done anything about the gain yet.
So, if we start now, if we apply this...
..this PSS if you connect to the system.
The next thing to do is to start to increase the gain.
So, if we start increasing the gain systems becoming better and better and better and better damped.
And then, at some points it becomes unstable.
So, what happened? Well, what happened is that at some point with the gain increasing we go to a point where control mode cross the limit.
And become unstable.
So, because you were not paying attention to what is happening with the control mode, control mode while PSS, which was tuned to damp electromechanical mode, contributed to eletromechanical mode moving to the left.
So, first the cross into stable region.
And then to become more and more stable, or more and more negative, if you like.
Control mode at the same time, which was initially stable.
And on the left hand side accelerated much faster with the increase of the PSS gain to the right.
So, at some point while electromechanical mode cross to the left and slowly was moving to the left.
Control mode was first moving to the right.
And destabilise the system.
So, what do we do in that case? In that case, we find out what was the value of the gain where control mode became unstable.
And then, we either halve or take one-third of that value of the gain, of critical gain of PSS.
And set that as appropriate gain of the PSS.
So, with this gain we ensure appropriate stability margin.
And the system is stabilised.
So, once we apply that gain.
Now, this PSS, this PSS has three lead-lag blocks.
So, three extra differential equations with four that we had previously.
The system model now has seven differential equations.
Therefore, system state matrix is 7 by 7.
Therefore, there will be seven eigenvalues.
And they are seven of those as you can see.
The system is stabilised now.
The eigenvalue, the eletromechanical mode improved dramatically or significantly.
So, the damping is -0.57 compared to +0.12.
And as you can see, the response is much much better damp, and oscillations disappear in less than 10 seconds.
So, the tuning of this PSS was successful.
What was actually happening if you look the behaviour in the system.
Original system was at the top left hand side, the red dot top left hand side.
When we installed PSS and increased the gain of PSS to improve transient stability.
First thing, stability in particular, we actually move the operating point, or the critical eigenvalue, from close to -1.5 to very close to 0.
So, the system actually became less stable.
Yes, transient stability improved but oscillations were less damped.
Then, we apply PSS.
And we start pushing that eigenvalue again to the left.
And we end up with the PSS gain increase where the green point is.
So, with the PSS at the green point, we have now a situation where with application of AVR we solve the problem of transient stability.
With application of PSS, we improve the damping.
So, with this final tuning, this is the full control satisfactory achieved.
Satisfactorily achieved.
Now, how do we actually choose where to place PSS? As I said before, that the thing to do that is to find PSS.
Find the...
..calculate open loop transfer function residues for all generators that are involved in the particular mode.
And the high value of open loop residues associated with inter-area modes indicate the best generators for installing PSS.
And here is the example.
So, this is now ten machine system.
In this ten machine system, three modes were found to be unstable.
And through calculation of participation factors we can see which generators are involved in which mode.
Obviously, the least damped mode number 2 is involving generator 9 alone.
So, there is a clear answer here.
If generator 9 is the most involved we are going to install PSS in generator 9.
So, for generator 9 we design PSS how it was described before.
We install it here, increase the gain.
And we can see that that PSS stabilise mode 2 significantly.
So, move it from unstable position to the far right.
To a very very stable position to the left.
Mode 3 was not affected at all.
Because generator 9 was not involved in mode 3.
So, installing PSS in generator 9 didn't really help.
Generator mode 1 was stabilised also.
But the effect in mode 1 was moderate.
But still we have unstable system.
Which has determined now stability is governed by instability of mode 3.
So, we need another PSS.
So, for the new system we calculate eigenvalue again, and calculate participation factors.
And based on participation factors clearly we have to install second PSS at generator 3.
Based on residue calculations and gain setting, we install that PSS.
And then we can see that by increasing the gain of PSS we move the mode 3 from unstable to stable region again.
So, the system is complete stabilised.
So, this is example basically of sequential tunings.
So, we tuned first PSS of generator 9.
And then PSS of generator 3.
PSS of generator 3 was tuned with the assumption that PSS of generator 9 is in existence.
If the PSS of generator 9 fails to operate.
The tuning of PSS of generator 3 may not have been as successful as originally.
Because the system that is now to control would be different than the one that it was designed for.
This is another case study that you can look on your own.
Where a same procedure is applied.
So, identify control mode, electromechanical mode, and then tune additional controller on SVC to SVC now... VSC plus high voltage DC.
So, using damping high voltage DC link to stabilise the system.
And clearly, this can be achieved.
This is what I was talking about earlier when I said that damping inter-area modes.
The most effective location for damping inter-area modes actually is somewhere in the system.
Not necessarily at any of the generating system.
But more likely to one of the FACTS, flexible alternating current transmission system devices or high voltage DC links because they are placed in the system where these oscillations are experienced.
 
Improving Large-Disturbance Stability, automated transcript 018-10-12 ---  
LECTURER: 
As illustrated in the previous example, the placement of PSS or dumping control at SVC or at high voltage DC line, we try to locate it in transmission system, can greatly improve stability.
So PSS do not have to be placed only at generators.
It actually can be much more effective in damping anterior oscillations if they are placed at one of those FACTS devices.
I already talked before about the effect of reducing transmission system reactants, so, these are examples of how these transmission system reactors can be reduced.
It's either by reducing the reactamce transmission circuit which is using a particular circuit configuration or conductor configuration or using more parallel circuits, parallel lines, transmission lines between two buses that will effectively reduce the reactors.
Or use transformers with lower leakage reactants or injection of series capacitors when we have to control the system after the fault.
Now, this obviously is connected with some very sophisticated control.
So speed of reinsertion, this connection after the fault is of the essence here.
Control of series elements.
Again, one of the most widely explored devices for this purpose are Thyristor Controlled Series Compensators or TCSCs as one from the family of FACTS devices because they can regulate the reactance, the series reactance of the line.
And in that way, by modulating reactance, they can interfere or affect the power transfer and therefore damp the installations.
The following slides show that application of FACTS across the world of some ten years ago.
They are, they have been present in many parts of the world, different, different number of this device has been installed.
And there are information about installations in different parts of the world.
One thing that is important to mention here, these are very expensive devices, very sophisticated, very capable of controlling various aspects of system performance, but generally very expensive and very large installations as you can see in the figures shown here.
The thing that is particularly worth mentioning is that the proliferation of FACTS devices has been restricted in a way due to their cost.
The cost is roughly 200,000 money units, but these are euros, dollars, pounds, pretty much yens.
Pretty much varies from country to country depending what the currency the countries use per megawatts.
So they are for the capacities.
We are talking about, we are talking about multi-million, multi-million costs.
One of the reasons why they have not been used more wisely is this cost, but the cost has been always balanced with the benefit, clearly.
The problem that we have in this respect is that they have been installed to correct or improve a particular system performance at a particular location without actually looking the effects on other locations and improvement of other system characteristics.
For example as we see, can control voltage very fast.
So that improves both power quality and voltage regulation.
As we see being shunt element will not affect the bus where it is installed, but also neighbouring buses.
So the benefit from installing as we see, would not be only for example, for a voltage sag regulation, but also for voltage regulation in general.
And the benefit will not be only at the bus where it is installed, but also to neighbouring buses.
Furthermore, if we add a simple damping control of that as we see, the dumping, the stability of the system can improve.
So there are various improvements that single device can bring and at various buses.
There haven't been studies in the past which would consider modern one benefit at modern one bus.
Once this is one, the result maybe actually that these devices are not as expensive as originally thought.
Considering that there is...
very difficult to build new transmission lines in modern power systems and that building high voltage DC lines may be expensive.
And even though if they're built and they are being built all around the world, some of the existing AC transmission lines would have to be enhanced or their transferability will have to be expense with installation of FACTS devices.
Therefore these proper tech and economic analysis with FACTS devices.
And considering all the benefits they can bring to all the buses.
They can bring many results in faster proliferation of these devices in the future because they will be needed.
Anyway, it will be a question of justification of cost.
And if these costs are looked at from a different angle, it may be that proliferation may be faster than initially expected.
 
Other Methods of Improving Large-Disturbance Stability, automated transcript 018-10-12 ---  
LECTURER: 
Now, in addition to applying series elements and a modality of this would be further devices same as with shunt elements.
But whether it's a series capacitor or shunt capacitor, series reactor or shunt reactor, this as a device it would be an on/off device typically with discrete bang-bang control.
If it is a mode of application through fax device, if we're... if you like emulating shunt capacitor or series capacitor, or shunt reactor or series reactor as SVS on or TCSC which they become fax devices, the effect is the same.
So with series capacitor, with series compensation, what we're actually doing we're affecting power transfer across the line.
We're either extending or reducing the line from the line that has both effect on power transfer and on voltage regulation across the line.
And this effect is basically affecting only the downstream bus.
The bus in the direction of power flow after the device.
If we're applying shunt compensation, this is device which is connected in parallel as the system bus.
And that device will not affect only the bus we disconnected but it will also increase the voltage at surrounding buses.
Now the problem with installation of shunt device is that they've to be larger generally.
Because they have to boost the if they are to have any appreciable affect on the bus voltage to which they are connected, then their size would depend on the short acidic capacitor in that bus.
So the stronger the bus is the larger device have to be.
But even though it has to be large, it will not only affect that bus but it will also affect neighbouring buses.
And then as I explained before, connecting shunt elements will result in the increase of the voltage at the location and neighbouring locations where the SVC is installed.
This increase in voltage is reflected in increase of electrical power that the system can't transfer or transmit.
In post - fault condition therefore, it increases deceleration area and it used be here.
If you look the power angle curve, then the connection of SVC or shunt capacitor results in increasing magnitude of the power angle curve therefore more power can be transferred after the fault and the system can be decelerated or damped...
oscillations and system acceleration.
Rotor acceleration can be damped better.
Now this can be the said controllable shunt elements or shunt reactors will be installed to consume reactive power.
And I mentioned that before in the context then I was talking about generators having to operate with the leading power factor.
This is the case in systems where we have a lot of underground cables which have higher capacitances.
And during the night and at the time of and at periods of light loading.
So when we have a light load in the system and cables with a high capacitance that may result in an accessibly unacceptably high voltages particularly during the night, then we need to do something to consume reactive power.
So in cases like that, we would install shunt reactors.
Otherwise shunt compensation can be either through it doesn't have to be capacitors.
It can be modulation control or Superconducting Magnetic Energy.
Storage system it can be supplementary SVC control, it can be braking resistors, combinational of SVC and braking resistors.
So all these devices are actually helping with improving system stability.
Examples further of installation of shunt and series compensation is we can see they are predominantly increasing deceleration area SVC and TCSC.
Both of them are helping with increase in deceleration area.
Because they act once the fault is removed.
And here are the examples with a system response with applied shunt compensation and the legends of these figures are self explanatory.
So for different setting in different size of shunt compensation we have different effect on the generator damping.
Dynamic braking is something that I would mention which is one same as first insertion of shunt and series compensation.
Dynamic braking is applied after the fault has occurred.
And so what we do actually switch in a shunt resistor for about half a second following a fault so to dissipate the energy and then again switch it off.
Obviously this is very important to have very good coordination in time and timing of switching in and out of these devices.
Examples of the fact of dynamic braking here you can see that the larger the device is the better it helps or the more it helps with system oscillations.
About second break at operation we've seen that if we have single line to ground fault, the acceleration is lower than in case of three phase fault.
Because with the single phase fault, we have only one line affected.
And power can be transmitted through other two lines.
So if we have a single phase fault which are most frequent faults in the system, typically some 65 to 70% in the system are of the faults in the system are single phase faults.
And if you do not have independent pole operation on the circuit breakers, we may disconnect all for the lines which will be wrong because that will obviously interrupt power transmission completely.
If you have independent operation, then each phase is open and close independently.
And then because of that we're enabling more power transfer or we're enabling power transfer through healthy lines which don't need to be disconnected.
Now this is obviously require more complex switching equipment on breakers because separate operating mechanism on each phase.
So we have different controllers for each phase that device is more expensive.
However, overall benefit resulting from these are substantial.
Fast valving is another mechanism for corrective control for control.
Often disturbance happen that I mentioned before, it is rapid closing and opening of steam valves to reduce the generator accelerating power.
Now this is the two options.
One is the main control valve, main inlet valve and the other is intercept valve.
Now main valve would mean that you shut down completely the whole steam turbine which is not advisable.
And it's connected to various risks.
So instead of that, the intercept valves are much more easy to operate.
And they control about 70% of the total unit power in comparison to control valves which control 30% of the power.
And they can intercept valve can close rapidly, very quickly be closed and opened.
So what we do, we have typically complete closure with about fraction of a second.
So within up to 0.4 seconds you can practically close the valve and cut down the mechanical power by 70%.
And then reopen it after 0.3 up to one second.
So we're basically reducing the accelerating years.
The moment the fault is...because fault would be cleared very, very quickly, not within 0.08 second but fault will be cleared within some 100 milliseconds.
So within that scope while the fault is all still lasting we're closing the intercept valve, reducing mechanical power and then we're reopening it slightly later.
So we're capturing both.
We're capturing the decelerating and accelerating areas.
So we're trying to reduce decelerating and increase accelerating area the same time.
This is the practice which has been and easy applied in power system around the world more probably I would look at it more in US and less in Europe.
And there are different settings.
So for example full opening in USA is within three to 10 seconds.
So they wait a bit longer for re-establishing the full power from the turbine while in Europe it's more if you like bang - bang control.
So it's a quick closure and then very first opening after opening after the so trying not to reduce the much power coming from the turbine.
In fact this is what intercept valve is.
So it controls as I said it controls about 70% of the power going through the turbine.
So it connects intermittent pressure, low pressure one, and low pressure two.
So three turbines are practically disconnected with an intercept valve while the main control valve is predominantly responsible for high pressure turbine only.
This is example of how the fast valving affects responses.
And you can see with different setting of the fast valving.
We have quite different responses in a multi - machine system.
Examples of comparing different corrective control actions, shunt compensation as we see is basically shunt compensation break dynamic braking with the injection of shunt resistors and first valving.
So we can see that there are different effects of different methods.
It appears not it appears but it has been found that basically with shunt capacitors, the best benefit can be achieved if they're placed at strategic locations.
In conclusion, there are various options that can be applied to improve transient stability.
The most widely used still is tuning power system stabilisers.
This is something that we do offline, in advance and assuming potential disturbance.
Here is potential notes calculating potential most may appear in a system.
And then tuning PSSs to cater for this disturbances and AVR obviously if the disturbance happens.
This has been done for many, many years.
And it has been proven to be a very efficient and effective way of controlling the power system.
There have been fewer applications of corrective measures like insertion of a braking resistors, installation of shunt of CSS capacitors and use of fast valving.
They have been applied but not as widely as tuning of power system control.
Because they are associated with more if you like more risky operation, more time dependent operation.
And power system engineer simply didn't want to take any unnecessary risk in that respect.
So with this new, with proliferation of these new devices all together and market forces, the dynamic structure, dynamic (INAUDIBLE) system will change.
Therefore the drive to apply more corrective measures may be higher and the options of applying corrective measures are currently being explored around the world and their cost effectiveness is assessed.
So this was all that I had to tell you about power systems dynamics.
I think you will enjoy these 10 or so hours of me talking to you.
The next part of the course will be about power quality and power system reliability.
And it will be delivered by doctors Victor Levi and Mathaios Panteli.
Thank you very much once again for listening to me.
And I wish you all the best with your exam.
