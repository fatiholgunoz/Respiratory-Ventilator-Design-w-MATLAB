# Respiratory-Ventilator-Design-w-MATLAB

We were requested to design a Mechanical Ventilator, which is used to aid patients in
extensive care units, who are struggling to breath on their own due to some medical complications.

The project started with the modelling of the lungs, in order to try the designed ventilator
models on. For this, we first created a Simulink Model with the electrical circuit equivalent given in
the project description. Then we acquired a transfer function which is the direct conversion of the
electrical circuit and compared this transfer function to our actual model. Then we reduced this fifth
order transfer function to a first order one, with the knowledge we gained in Controls Engineering
Courses and with the help of MATLAB. Finally we created the equivalent electrical circuit of this
reduced transfer function, and used this simple model onwards.

In the second part, we were requested to design to different modes for the Mechanical
Ventilator, namely Pressure Controlled and Volume Controlled Ventilation. Both were created by
following the steps carefully. The results were promising, the output graphs of both the models were
as desired, generating a healthy tidal volume plot.

For the third and last part, we finally added the patient diaphragm activity to both PCV and
VCV models, as these ventilators will sometimes be used on half-awake patients, who might start to
breath on their own, often inadequately. We again succesfully generated the desired tidal volume
graphs, under different lung resistances and capacitances.
