[index.html](https://github.com/user-attachments/files/33471536/index.html)
# fitpulse-gym-frontend.
Módulo Frontend del sistema FitPulse Gym System desarrollado en HTML, CSS y JavaScript para la gestión de socios, control de asistencia y asignación de rutinas.
[styles.css](https://github.com/user-attachments/files/33471538/styles.css)body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background-color: #f0f2f5;
    margin: 0;
    padding: 20px;
}

header {
    text-align: center;
    background: #1e293b;
    color: white;
    padding: 15px;
    border-radius: 8px;
    margin-bottom: 25px;
}

.contenedor {
    display: flex;
    gap: 20px;
    justify-content: center;
    flex-wrap: wrap;
}

.tarjeta {
    background: white;
    padding: 25px;
    border-radius: 10px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.08);
    width: 340px;
}

h2 {
    font-size: 1.1rem;
    color: #334155;
    margin-top: 0;
}

label {
    display: block;
    margin-top: 12px;
    font-size: 0.9rem;
    color: #64748b;
}

input, select {
    width: 100%;
    padding: 10px;
    margin-top: 5px;
    border: 1px solid #cbd5e1;
    border-radius: 6px;
    box-sizing: border-box;
}

button {
    width: 100%;
    padding: 12px;
    margin-top: 18px;
    background-color: #2563eb;
    color: white;
    border: none;
    border-radius: 6px;
    font-weight: bold;
    cursor: pointer;
}

button:hover {
    background-color: #1d4ed8;
}

.btn-acceso {
    background-color: #059669;
}

.btn-acceso:hover {
    background-color: #047857;
}

.estado-box {
    margin-top: 15px;
    padding: 10px;
    border-radius: 6px;
    display: none;
    font-size: 0.85rem;
    text-align: center;
}
