# LEAVES
Based on the open datasets of ASAS-SN, Gaia and ZTF, we construct a compatible light curve dataset named LEAVES for automated recognition of variable stars, from the work " LEAVES: An Expandable Light Curve Dataset for Automatic Classification of Variable Stars ". The dataset contains a total of 979,962 variable and 134,592 non-variable light curves, in which the supported variables are divided into 6 superclasses and 9 subclasses. We validate the compatibility of the data set through experiments and use it to train a hierarchical random forest classifier. 


We provide the light curves of these objects by class in csv files in https://drive.google.com/drive/folders/1R8r4oBXKxLdC6puUkS4IUx4VTY_lTluW. The composition of LEAVES is shown in table below:

<table>
        <tr>
        <th>Class</th>
        <th>Subclass</th>
        <th>ASAS-SN_V</th>
        <th>ASAS-SN_g</th>
        <th>ZTF</th>
        <th>Gaia</th>
        <th>Total</th>
    </tr>
    <tr>
        <td rowspan="2">Eclipsing binaries(EB)</td>
        <td>EA</td>
        <td>37463</td>
        <td>10695</td>
        <td>29198</td>
        <td rowspan="2">6785</td>
        <td rowspan="2">421025</td>
    </tr>
    <tr>
        <td>EW</td>
        <td>57058</td>
        <td>22724</td>
        <td>257093</td>
    </tr>
    <tr>
        <td>Rotational variables(ROT)</td>
        <td>ROT</td>
        <td>16850</td>
        <td>4202</td>
        <td>98060</td>
        <td> </td>
        <td>119112</td>
    </tr>
    <tr>
        <td rowspan="2">RR Lyrae(RR)</td>
        <td>RRAB</td>
        <td>13244</td>
        <td>10981</td>
        <td>17598</td>
        <td rowspan="2">840</td>
        <td rowspan="2">61366</td>
    </tr>
    <tr>
        <td>RRC</td>
        <td>5959</td>
        <td>3624</td>
        <td>9120</td>
    </tr>
    <tr>
        <td>Cepheids(CEP)</td>
        <td>CEP</td>
        <td>1003</td>
        <td>405</td>
        <td>1074</td>
        <td>2</td>
        <td>2484</td>
    </tr>
    <tr>
        <td rowspan="2">Long period variables(LPV)</td>
        <td>SR</td>
        <td>140997</td>
        <td>143376</td>
        <td>46738</td>
        <td rowspan="2">5095</td>
        <td rowspan="2">355374</td>
    </tr>
    <tr>
        <td>M</td>
        <td>7884</td>
        <td>6133</td>
        <td>5151</td>
    </tr>
    <tr>
        <td>Delta Scuti(DSCT)</td>
        <td>DSCT</td>
        <td>3718</td>
        <td>939</td>
        <td>13944</td>
        <td> </td>
        <td>18601</td>
    </tr>
    <tr>
        <td>Non-var</td>
        <td>Non-var</td>
        <td>134592</td>
        <td> </td>
        <td> </td>
        <td> </td>
        <td>134592</td>
    </tr>
</table>

The full data set and machine learning models are also available and will be released officially at the China National Astronomical Data Center. 
