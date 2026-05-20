**[點此直接在瀏覽器線上體驗動態模擬器](https://abckenny654159-kuanchuan.github.io/control-system-simulator/)**
**[Click This](https://abckenny654159-kuanchuan.github.io/control-system-simulator/)**

# Control System Simulator

An interactive, web-based automatic control simulator designed to help users deeply understand and practice the tuning process of various control algorithms through intuitive physics animations and real-time response charts.

---

## Key Features

* **Multi-Controller Support:**
  * **PID Control:** The classic Proportional-Integral-Derivative control.
  * **LQR Control (Linear Quadratic Regulator):** Optimal control based on state-space representation and weight matrices $Q$ and $R$.
  * **Sliding Mode Control (SMC):** Robust control featuring equivalent and switching control terms, allowing visualization of the sliding surface $s$ dynamics.
  * **Fuzzy Control:** Intelligent control utilizing a 3x3 semantic rule base and weighted average defuzzification.
* **Real-time Physics Simulation:** Dynamically animates the horizontal displacement of a point mass under the influence of control force $u$, velocity $v$, and external disturbance $d$.
* **Dynamic Response Charts:** Plots real-time trends of tracking error and individual control components over time.
* **Advanced Tuning Tools:**
  * Supports the **Ziegler-Nichols Method** to automatically calculate and apply Kp, Ki, and Kd parameters.
  * Features a built-in **Custom PID Function** editor, allowing users to override the control logic directly using JavaScript in the browser!
* **Disturbance Simulation:** Simulates external forces including Sine, Square, Triangle waves, and Random Noise to test the controller's robustness.

---

## Tech Stack

* **Frontend:** Vanilla JavaScript, HTML5 Canvas, CSS Grid
* **Math & Physics:** Euler method for numerical integration of differential equations ($\frac{dx}{dt}$, $\frac{dv}{dt}$)

---

## How to Use

1. Select the type of controller you want to practice with.
2. Adjust the system parameters such as plant mass, damping ratio, initial position, or the target setpoint.
3. Click **"Start"** to observe the dynamic response of the system.
4. Experiment with tuning the controller parameters (e.g., Kp/Ki/Kd gains or Q/R matrices) to guide the system to a perfectly stable state without overshoot!

---

## 核心功能 / Key Features

* **多種控制器支援 / Multi-Controller Support:** * **PID 控制 (PID Control):** 經典的比例-積分-微分控制。
  * **LQR 控制 (Linear Quadratic Regulator):** 基於狀態空間、權重矩陣 $Q$ 與 $R$ 的最佳控制。
  * **滑膜控制 (Sliding Mode Control, SMC):** 具備等效控制與切換控制項，可觀察滑動面 $s$ 的動態。
  * **模糊控制 (Fuzzy Control):** 基於 3x3 語意規則表與加權平均輸出的智慧控制。
* **即時物理模擬 / Real-time Physics Simulation:** 動態繪製質點（Mass）在控制力 $u$、速度 $v$ 與外部擾動 $d$ 作用下的水平位移。
* **動態響應圖表 / Dynamic Response Charts:** 即時繪製誤差（Error）以及各控制項隨時間變化的趨勢圖表。
* **高級調參工具 / Advanced Tuning Tools:** * 支援 **齊格勒－尼科爾斯方法 (Ziegler-Nichols Method)** 自行計算並套用 Kp, Ki, Kd。
  * 內建 **自訂 PID 函數 (Custom PID Function)** 編寫區，允許直接在網頁上用 JavaScript 覆寫控制邏輯！
* **外部擾動模擬 / Disturbance Simulation:** 支援正弦波、方波、三角波及隨機雜訊等外力干擾，考驗控制器的魯棒性（Robustness）。

---

## 技術 / Tech Stack

* **Frontend:** Vanilla JavaScript, HTML5 Canvas, CSS Grid
* **Math & Physics:** Euler method for differential equations (dx/dt, dv/dt)

---

## 如何使用 / How to Use

1. 選擇你想練習的控制器類型。
2. 調整質點質量、阻尼、初始位置或目標位置（Target）。
3. 點擊「開始」觀察系統響應。
4. 嘗試調整控制器參數（如 Kp/Ki/Kd 或 Q/R 矩陣），使系統達到穩定且無過衝（Overshoot）的完美狀態！
