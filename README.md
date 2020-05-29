# CppND-Traffic-L1

Tasks finished are in:
- `src/TrafficSimulator-L1.cpp`:  `nVehicles` (rand number)
- `src/Vehicle_Student.cpp`:  `_threads.emplace_back(std::thread(&Vehicle::drive, this));` in `Vehicle::simulate()`
- `src/TrafficObject.cpp`:
  ```
    for(auto &t : _threads){
      t.join();
    }
  ```
