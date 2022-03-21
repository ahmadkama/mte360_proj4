clear all; clc; close all;

b1 = 0.0097;
b2 = 0.00097122;
d1 = 0.793;
d2 = 0.0793;
p = 22.222222222;
m1 = 0.00031218;
m2 = 0.00016858;
w_d = 19.9466;
k = 0.0466;
zeta = 0.255;
w_n = 20.6287;
c = 0;
Ts = 0.001;

kp = 11.993;
q = 1000;

traj = load('trajectory_data.mat');
t = traj.t;
xr = traj.s;

open('flexible_drive_filtered.mdl');
sim('flexible_drive_filtered.mdl');
