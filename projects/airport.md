#Симулация на полетите в летище

Малко летище има само с една писта. Във всяка единица от време само един самолет може да кацне или само един самолет може да излети. В даден момент от време пистата може да е или празна, или самолет да каца, или самолет да излита. Възможно е няколко самолета да чакат за кацане или за излитане. Да се напише програма, която симулира поведението на летището. За целта да се използват две опашки от самолети landing (за кацане) и takeoff (за излитане), в които самолетите да чакат. След получаване на заявка от самолет за кацане или за излитане, симулацията да обслужи самолета от главата на опашката за кацане landing и само ако опашката landing е празна да позволи да излети самолет. Симулацията да протече за периода от време endtime, което е реално число. На всяка стъпка от време се появява нов самолет за кацане с вероятност L процента и се появява нов самолет за излитане с вероятност T процента.

####Да се напише програма, която въвежда числата endtime, L, T и прави симулация на излитането и кацането на самолети, като изведе някои статистики като:

* брой на кацналите самолети;

* брой на излетелите самолети;

* брой на самолетите, на които е направен отказ за незабавно кацане или излитане (т.е. се е наложило да изчакат);

* среден брой на чакащите за кацане и за излитане самолети;

* процент на времето, когато пистата е свободна;

* средно време за чакане за кацане.

#####Генерирането на самолети да се осъществява по случаен начин. За целта да се използва функцията rand, в резултат от изпълнението на която се получава цяло число от 0 до RAND_MAX (RAND_MAX е константа, различна за отделните реализации).