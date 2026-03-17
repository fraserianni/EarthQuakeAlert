# Earthquake Early Warning Experiments

This repository contains experiments and prototypes for building an earthquake early warning system using seismic data from INGV and ObsPy.

## Project Goal

The goal of this project is to understand how to:

- Access seismic data from INGV using FDSN services
- Monitor seismic stations in near real-time
- Process waveform data
- Detect potential P-wave arrivals
- Build a basic early warning logic

## Project Structure

- `notebooks/` → Jupyter notebooks for experiments and step-by-step analysis  

## Current Progress

- [x] Discover nearby seismic stations
- [x] Visualize stations on interactive maps
- [x] Read waveform data from INGV
- [x] Implement near real-time monitoring
- [ ] Signal filtering
- [ ] P-wave detection (STA/LTA)
- [ ] Multi-station validation
- [ ] Alert generation

## Technologies Used

- Python
- ObsPy
- Matplotlib
- Folium
- Jupyter Notebook

## How It Works (Concept)

1. Retrieve seismic stations from INGV
2. Select nearest stations
3. Continuously read waveform data
4. Process and filter signals
5. Detect anomalies (possible P-wave)
6. Validate across multiple stations
7. Generate alerts

## Notes

This is an experimental and educational project.  
It is not intended for real-world safety or operational use.

## Author

Francesco Serianni
