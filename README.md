# Continuous_Algorithms_For_Binary_Antenna_Placement

**Programmer:shipit:**: Zakaria Abdelmoiz DAHI, University of Malaga, Spain. 

**About:** This repositiory implements the binary variants of the algorithms devised and studied in [1] that solves the antenna positioning problem in cellular networks using several types of antennas, named directive, directional and circular.

- [1] **Dahi, Z.A.E.M.**, Mezioud, C., Draa, A. (2015). Binary Bat Algorithm: On The Efficiency of Mapping Functions When Handling Binary Problems Using Continuous-variable-based Metaheuristics. In: Amine, A., Bellatreche, L., Elberrichi, Z., Neuhold, E., Wrembel, R. (eds) Computer Science and Its Applications. CIIA 2015. IFIP Advances in Information and Communication Technology, vol 456. Springer, Cham. https://doi.org/10.1007/978-3-319-19578-0_1 

**How: :green_book:** 

    - To excuted just navigate to the folder BBAs or GGA.
    - Choose the folder of the variant you want to test `BA_Angle_modulation, ...
    - Excute the main.py file.
    - **NB**: I am using a cluster for my experiments, so if you are using a local machine just uncomment the lines I dedicated to it.


**Folders Hiearchy :open_file_folder:**
    
    - Code:
        - BBAs: contains seven binary variants of the bat algorithm:
            - Angle Modulation.
            - Grate value priority.
            - Normalised.
            - Quantum-inspired.
            - Rounding.
            - Sigmoid.
        - GGAs: Implements the generational genetic algorithm.
    - Results:
        - SQUARED_SHAPED_ANTENNA: results using squared antennas.
        - DIRECTIVE_SHAPED_ANTENNA: results using directive antennas.
        - CIRCLE_SHAPED_ANTENNA: results using circular antennas.
        
**Demo**

![09-May-2013](https://user-images.githubusercontent.com/68249696/221611990-facff88a-fbb3-4f82-a50d-ad62096e0836.gif)
![10-May-2013](https://user-images.githubusercontent.com/68249696/221612154-137323d9-0831-4876-ac3e-21fbd4edb0b6.gif)
![09-May-2013](https://user-images.githubusercontent.com/68249696/221612194-b61e48b7-0a05-469a-a723-0016dbcde79f.gif)
