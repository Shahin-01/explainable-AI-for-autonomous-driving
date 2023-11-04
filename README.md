# Explainable Autonomous Driving
In this repository, we provide a compendium of explainable AI (XAI)-based approaches for autonomous driving. These studies are primarily about developing XAI approaches for autonomous driving with some forms of convolutional neural network (CNN), reinforcement learning (RL), and recurrent neural  network (RNN) architectures. 

1. [VisualBackProp: visualizing CNNs for autonomous driving](https://arxiv.org/abs/1611.05418v1), 2016 </br>
**Summary**: This study explains predictions of CNNs in end-to-end autonomous driving by showing which sets of pixels of an input image contribute to the CNNs' predictions. 

2. [Interpretable learning for self-driving cars by visualizing causal attention](https://openaccess.thecvf.com/content_iccv_2017/html/Kim_Interpretable_Learning_for_ICCV_2017_paper.html), 2017 </br>
**Summary**: The authors use a visual attention model to train a CNN from images to steering angle, and apply a causal filtering to find out which parts of input mainly influence the network's output. 

3. [Textual Explanations for Self-Driving Vehicles](https://openaccess.thecvf.com/content_ECCV_2018/html/Jinkyu_Kim_Textual_Explanations_for_ECCV_2018_paper.html), 2018 </br>
**Summary**: The study uses a visual attention model to train a CNN end-to-end from images and then employs an attention-based video-to-text model to generate textual explanations of the decisive actions. 

4. [Out of Sight But Not Out of Mind: An Answer Set Programming Based Online Abduction Framework for Visual Sensemaking in Autonomous Driving](https://www.ijcai.org/proceedings/2019/260), 2019 </br>
**Summary**: The authors develop an answer set programming-based abductive reasoning framework for online sensemaking that combines knowledge representation and computer vision in an online manner to explain dynamics of traffic scenarios, particularly occlusion scenes.

5. [Visual Scene Understanding for Autonomous Driving Using Semantic Segmentation](https://link.springer.com/chapter/10.1007/978-3-030-28954-6_15), 2019 </br>
**Summary**: The paper propose a semantic segmentation model implemented as a pixel-wise classification that explains underlying real-time perception of the environment.

6. [End-To-End Interpretable Neural Motion Planner](https://openaccess.thecvf.com/content_CVPR_2019/html/Zeng_End-To-End_Interpretable_Neural_Motion_Planner_CVPR_2019_paper.html), 2019 </br>
**Summary**: The authors introduce a neural motion planner for autonomous driving in complex urban scenarios using raw LIDAR data and a HD map.

7. [ I Drive - You Trust: Explaining Driving Behavior Of Autonomous Cars](https://dl.acm.org/doi/abs/10.1145/3290607.3312817?casa_token=2L1pKflGKisAAAAA:_K-4szLXrBBbdUFByQ4r3vJvABTHFdnmZ2QGTy49NhWIFJtVzUQuedpvXPIdviNLIP9x6BuUxwLl), 2019 </br>
**Summary**: A user study is performed: The authors identify a mental model of users for determining an effective practical implementation of an explanation interface for self-driving vehicles.

8. [Explaining Autonomous Driving by Learning End-to-End Visual Attention](https://openaccess.thecvf.com/content_CVPRW_2020/html/w20/Cultrera_Explaining_Autonomous_Driving_by_Learning_End-to-End_Visual_Attention_CVPRW_2020_paper.html), 2020 </br>
**Summary**: The authors propose conditional imitation learning with an end-to-end visual attention model that identifies parts of images that have a higher influence on predictions.

9. [“I’d like an Explanation for That!”Exploring Reactions to Unexpected Autonomous Driving](https://dl.acm.org/doi/abs/10.1145/3379503.3403554?casa_token=mZfjuDrG404AAAAA:pFmM2MD1wiEGbck3CRIMSjdLbhZgxOEoY4Y4HxKyBcbKFfBOpSx1HVeQSUgsU9dHSQtZBUywjZ0P), 2020 </br>
**Summary**: The authors explore situations where explanations are needed and what relevant methods are possible for these situations.

10. [Explainable Object-Induced Action Decision for Autonomous Vehicles](https://openaccess.thecvf.com/content_CVPR_2020/html/Xu_Explainable_Object-Induced_Action_Decision_for_Autonomous_Vehicles_CVPR_2020_paper.html), 2020 </br>
**Summary**: The authors propose object-induced actions with explanations for predictions of autonomous cars, and introduce a new dataset called BDD-OIA, annotated with 21 explanation templates on a set of 4 actions.

11. [Advisable Learning for Self-Driving Vehicles by Internalizing Observation-to-Action Rules](https://openaccess.thecvf.com/content_CVPR_2020/html/Kim_Advisable_Learning_for_Self-Driving_Vehicles_by_Internalizing_Observation-to-Action_Rules_CVPR_2020_paper.html), 2020 </br>
**Summary**: The paper proposes an approach that leverages human advice to learn vehicle control.

12. [Interpretable safety validation for autonomous vehicles](https://ieeexplore.ieee.org/abstract/document/9294490), 2020 </br>
**Summary**: The authors introduce a technique to identify interpretable failures of autonomous vehicles using signal temporal logic expressions in an unprotected left turn and pedestrian crossing scenarios

13. [Autodiscern: Autonomous driving using common sense reasoning](https://arxiv.org/abs/2110.13606), 2021 </br>
**Summary**: The study introduces AUTO-DISCERN, a system that incorporates commonsense reasoning with answer set programming to automate explainable decision-making for self-driving cars.

14. [Toward explainable and advisable model for self-driving cars](https://onlinelibrary.wiley.com/doi/full/10.1002/ail2.56), 2021 </br>
**Summary**: Similar to [11], the authors present an approach that leverages human advice to learn vehicle control.

15. [Human-Vehicle Cooperation on Prediction-Level: Enhancing Automated Driving with Human Foresight](https://ieeexplore.ieee.org/abstract/document/9669247?casa_token=6bmn5am8jJYAAAAA:JcnJyCi3anhYmEcKYdgDWnAaD48CJfdetGLcCVTZmD1FC0EhEWTquOaEfmEV62oHsF2KViqB), 2021 </br>
**Summary**: The authors propose a technique enabling a human driver to provide scene forecasting to an intelligent driving system using a purposeful gaze.

16. [Towards Accountability: Providing Intelligible Explanations in Autonomous Driving](https://ieeexplore.ieee.org/abstract/document/9575917?casa_token=z32codFXOBoAAAAA:CNk_iqWA55yViWLjCLnGns6KadoE2GuHsFBp0XWmyUD6VX5-ZL2Tm0e_xcZdru82bU9E1dk3), 2021 </br>
**Summary**: The study propose a tree-based representation and use human evaluation in a variety of driving scenarios and generate Why, Why Not, What If, and What explanations for driving situations.

17. [Interpretable End-to-End Urban Autonomous Driving With Latent Deep Reinforcement Learning](https://ieeexplore.ieee.org/abstract/document/9346000?casa_token=QVOn9WP5hT4AAAAA:AouY-wnaPy3yR7RBO4ZfSnJQsOAENMgIh3CgwIOvRfFJFq3JfVw_3QC5ihT9zRqaHFhvJvVC), 2021 </br>
**Summary**: The study introduces a sequential latent environment model learned with RL and a probabilistic graphical model-based approach that can interpret autonomous vehicles’ actions. 

18. [Learning Interpretable End-to-End Vision-Based Motion Planning for Autonomous Driving with Optical Flow Distillation](https://ieeexplore.ieee.org/abstract/document/9561334?casa_token=-b497m0SHTAAAAAA:dIoFX2iTBU3wxrNTYO_1DLVLnSJXZiPd9luQDBp6hg-av1ROQ7I_j67jvDLyd--p3Rl4mKV7), 2021 </br>
**Summary**: The authors propose an interpretable end-to-end vision-based motion planning (IVMP) to interpret the underlying actions of an intelligent vehicle.

19. [Interpretable Goal-based Prediction and Planning for Autonomous Driving](https://ieeexplore.ieee.org/abstract/document/9560849?casa_token=knn0E8YqAN8AAAAA:GnWJPKpGZsO4hY_2ieqDAo_QLhCnsyNtdi36Rk-27Kg_qmiaEs4th26vblnZDZovXidD7o7X), 2021 </br>
**Summary**: The authors present an integrated prediction and planning system for autonomous driving that uses rational inverse planning and Monte Carlo Tree Search to recognise the goals of other vehicles and plan the motion maneeuvers of the autonomous car.

20. [Uncovering Interpretable Internal States of Merging Tasks at Highway On-Ramps for Autonomous Driving Decision-Making](https://ieeexplore.ieee.org/abstract/document/9512609?casa_token=SGeImCnfH4sAAAAA:JFHQAbCjUkn2up7YD5VuVTiljQqmrZszN0qCvvVfSJYredH69acbJZi-UFewk-L6rHNhGlbe), 2021 </br>
**Summary**: The authors approach lane merging task as a dynamic process and integrate internal states into joint Hidden Markov Model (HMM) and Gaussian Mixture Regression (GMM).

21. [Interpretable Goal Recognition in the Presence of Occluded Factors for Autonomous Vehicles](https://ieeexplore.ieee.org/abstract/document/9635903?casa_token=KY7slSt4mFsAAAAA:tYdC2LG8vEaihQw4z4joDSuHC7AtjtGQcu75kdIx8NldmYwxiKAFdYUEGm1ke4cB4A8rYpSV), 2021 </br>
**Summary**: The study introduces an interpretable inverse-planning algorithm for joint goal and occluded factor inference, and show how it can be integrated into Monte Carlo Tree Search action selection.

22. [GRIT: Fast, Interpretable, and Verifiable Goal Recognition with Learned Decision Trees for Autonomous Driving](https://ieeexplore.ieee.org/abstract/document/9636279?casa_token=klfgL_8NLVMAAAAA:JY1CZ2Te_1aq7whGbjJDw1vxStmq_JqrXaLMgl1b6PKDAOHvGYBnIGQa0BadmiM0TMWf-AY5), 2021 </br>
**Summary**: The authors present Goal Recognition with Interpretable Trees (GRIT), a goal recognition system that attains safety and interpretability
objectives using decision trees trained on vehicle trajectory data.

### Reference

Detailed analysis and discussion of these studies are available are in the following article:
     
    @article{atakishiyev2021explainable,
    title={Explainable Artificial Intelligence for Autonomous Driving: A Comprehensive Overview and Field Guide for Future Research Directions},
    author={Atakishiyev, Shahin and Salameh, Mohammad and Yao, Hengshuai and Goebel, Randy},
    journal={arXiv preprint arXiv:2112.11561},
    year={2021}
    }

The article can be viewed [here.](https://arxiv.org/abs/2112.11561)
