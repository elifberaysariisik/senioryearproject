The aim of this project is to design a radio-navigation subsystem that can perform delta-position measurements using RF signals to provide reliable replacement for GNSS-based navigation systems that are vulnerable to challenges including signal distortion, multipath interference etc. The project requested by ASELSAN will be implemented in two stages: in Phase 1, one RF transmitter and one RF receiver will be used for 1D movement calculation, and in Phase 2, three RF transmitters and one RF receiver will be used for 2D movement calculation. Adalm-Pluto SDRs will serve as both transmitter and receiver. Implementing essential algorithms, such as Phase-Locked Loop (PLL) for phase and frequency synchronization, Delay Locked Loop (DLL) for code tracking and clock synchronization algorithm for clock alignment of Adalm-Pluto SDRs, is the main focus of the solution strategy. By reducing noise, multipath effects and clock errors, these algorithms provide accurate and dependable signal capture. MATLAB will be utilized for algorithm development, signal transmission and storage of received data while GNU radio will enable real-time signal transmission and acquisition. To assess system performance under various circumstances, signal analysis will consider issues like multipath interference and Doppler shifts. Validation will involve controlled transmission and reception tests, autocorrelation and cross-correlation analysis of delay and phase offsets, noise and multipath impact simulations, and real-time tests. The final product will consist Raspberry Pi to maintain more portable and user-friendly product for end users. The performance of the system will be evaluated based on its ability to achieve maximum error of ±5 cm in delta-position calculation. An affordable, GNSS-independent navigation system that delivers accurate delta-position calculation is the expected results of the project. ![Uploading image.png…]()
