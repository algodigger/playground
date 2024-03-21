### Install MLflow with pip

Install MLflow using pip:

```bash
pip install mlflow


#### Enable MLflow Server as a Service

```bash
sudo nano /etc/systemd/system/mlflow.service


paste this

[Unit]
Description=MLflow Server
After=network.target

[Service]
User=<your_username>
Environment="MLFLOW_HOME=/path/to/your/mlflow_home"
ExecStart=/path/to/your/mlflow_executable server --host 0.0.0.0 --port 5000
Restart=always

[Install]
WantedBy=multi-user.target

#### Reload systemd to apply the changes:

```bash
sudo systemctl daemon-reload

#### Start the MLflow service:

```bash
sudo systemctl status mlflow



#### Enable the MLflow service to start on boot:

```bash
sudo systemctl daemon-reload


#### Check the status of the MLflow service:

```bash
sudo systemctl status mlflow

