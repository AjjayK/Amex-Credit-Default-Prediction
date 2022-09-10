# **American Express - Default Prediction**
<p style='margin-top:0cm;margin-right:0cm;margin-bottom:8.0pt;margin-left:-20.45pt;line-height:107%;font-size:15px;font-family:"Calibri",sans-serif;text-indent:41.75pt;'><span style='font-family:"Open Sans",sans-serif;'>Predict if a customer will default in the future</span></p>

---

### **Notebooks**
#### EDA_and_Deep_Learning.ipynb
- Contains a EDA tool built using Plotly and Dash which displays histogram, boxplot and correlation information for the selected variable
- Contains Deep Neural Decision Tree and Deep Neural Forest Model which predicts credit default

#### LGBM.ipynb
- Contains Light Gradient Boosting Machine model

---

### **Results**
### **Conclusion**

1.   LGBM (Model in other notebook) stands out to be better in terms of metrics (Score - 0.79546 and Categorical Accuracy on training data - 92.87%)
2.   Amex Metric for Deep Decision Forest Model was better than Deep Neural Decision Tree since Forest Model is an ensemble model

Overall results are given in the table below

<table style="margin-left:21.3pt;border-collapse:collapse;border:none;">
    <tbody>
        <tr>
            <td style="width: 134.85pt;border: 1pt solid windowtext;padding: 0cm 5.4pt;vertical-align: top;">
                <p style='margin-top:0cm;margin-right:0cm;margin-bottom:0cm;margin-left:0cm;line-height:normal;font-size:15px;font-family:"Calibri",sans-serif;'><strong><span style='font-size:16px;font-family:"Open Sans",sans-serif;'>Model</span></strong></p>
            </td>
            <td style="width: 134.85pt;border-top: 1pt solid windowtext;border-right: 1pt solid windowtext;border-bottom: 1pt solid windowtext;border-image: initial;border-left: none;padding: 0cm 5.4pt;vertical-align: top;">
                <p style='margin-top:0cm;margin-right:0cm;margin-bottom:0cm;margin-left:0cm;line-height:normal;font-size:15px;font-family:"Calibri",sans-serif;'><strong><span style='font-size:16px;font-family:"Open Sans",sans-serif;'>Categorical Accuracy on Training Data</span></strong></p>
            </td>
            <td style="width: 134.9pt;border-top: 1pt solid windowtext;border-right: 1pt solid windowtext;border-bottom: 1pt solid windowtext;border-image: initial;border-left: none;padding: 0cm 5.4pt;vertical-align: top;">
                <p style='margin-top:0cm;margin-right:0cm;margin-bottom:0cm;margin-left:0cm;line-height:normal;font-size:15px;font-family:"Calibri",sans-serif;'><strong><span style='font-size:16px;font-family:"Open Sans",sans-serif;'>Amex Metric on Training Data</span></strong></p>
            </td>
            <td style="width: 134.9pt;border-top: 1pt solid windowtext;border-right: 1pt solid windowtext;border-bottom: 1pt solid windowtext;border-image: initial;border-left: none;padding: 0cm 5.4pt;vertical-align: top;">
                <p style='margin-top:0cm;margin-right:0cm;margin-bottom:0cm;margin-left:0cm;line-height:normal;font-size:15px;font-family:"Calibri",sans-serif;'><strong><span style='font-size:16px;font-family:"Open Sans",sans-serif;'>Amex Metric on Test Data</span></strong></p>
            </td>
        </tr>
        <tr>
            <td style="width: 134.85pt;border-right: 1pt solid windowtext;border-bottom: 1pt solid windowtext;border-left: 1pt solid windowtext;border-image: initial;border-top: none;padding: 0cm 5.4pt;vertical-align: top;">
                <p style='margin-top:0cm;margin-right:0cm;margin-bottom:0cm;margin-left:0cm;line-height:normal;font-size:15px;font-family:"Calibri",sans-serif;'><span style='font-size:16px;font-family:"Open Sans",sans-serif;'>LGBM</span></p>
            </td>
            <td style="width: 134.85pt;border-top: none;border-left: none;border-bottom: 1pt solid windowtext;border-right: 1pt solid windowtext;padding: 0cm 5.4pt;vertical-align: top;">
                <p style='margin-top:0cm;margin-right:0cm;margin-bottom:0cm;margin-left:0cm;line-height:normal;font-size:15px;font-family:"Calibri",sans-serif;text-align:center;'><span style='font-size:16px;font-family:"Open Sans",sans-serif;'>92.8759%</span></p>
            </td>
            <td style="width: 134.9pt;border-top: none;border-left: none;border-bottom: 1pt solid windowtext;border-right: 1pt solid windowtext;padding: 0cm 5.4pt;vertical-align: top;">
                <p style='margin-top:0cm;margin-right:0cm;margin-bottom:0cm;margin-left:0cm;line-height:normal;font-size:15px;font-family:"Calibri",sans-serif;text-align:center;'><span style='font-size:16px;font-family:"Open Sans",sans-serif;'>0.6813</span></p>
            </td>
            <td style="width: 134.9pt;border-top: none;border-left: none;border-bottom: 1pt solid windowtext;border-right: 1pt solid windowtext;padding: 0cm 5.4pt;vertical-align: top;">
                <p style='margin-top:0cm;margin-right:0cm;margin-bottom:0cm;margin-left:0cm;line-height:normal;font-size:15px;font-family:"Calibri",sans-serif;text-align:center;'><span style='font-size:16px;font-family:"Open Sans",sans-serif;'>0.7954</span></p>
            </td>
        </tr>
        <tr>
            <td style="width: 134.85pt;border-right: 1pt solid windowtext;border-bottom: 1pt solid windowtext;border-left: 1pt solid windowtext;border-image: initial;border-top: none;padding: 0cm 5.4pt;vertical-align: top;">
                <p style='margin-top:0cm;margin-right:0cm;margin-bottom:0cm;margin-left:0cm;line-height:normal;font-size:15px;font-family:"Calibri",sans-serif;'><span style='font-size:16px;font-family:"Open Sans",sans-serif;'>Deep Neural Decision Tree</span></p>
            </td>
            <td style="width: 134.85pt;border-top: none;border-left: none;border-bottom: 1pt solid windowtext;border-right: 1pt solid windowtext;padding: 0cm 5.4pt;vertical-align: top;">
                <p style='margin-top:0cm;margin-right:0cm;margin-bottom:0cm;margin-left:0cm;line-height:normal;font-size:15px;font-family:"Calibri",sans-serif;text-align:center;'><span style='font-size:16px;font-family:"Open Sans",sans-serif;'>90.4552%</span></p>
            </td>
            <td style="width: 134.9pt;border-top: none;border-left: none;border-bottom: 1pt solid windowtext;border-right: 1pt solid windowtext;padding: 0cm 5.4pt;vertical-align: top;">
                <p style='margin-top:0cm;margin-right:0cm;margin-bottom:0cm;margin-left:0cm;line-height:normal;font-size:15px;font-family:"Calibri",sans-serif;text-align:center;'><span style='font-size:16px;font-family:"Open Sans",sans-serif;'>0.7907</span></p>
            </td>
            <td style="width: 134.9pt;border-top: none;border-left: none;border-bottom: 1pt solid windowtext;border-right: 1pt solid windowtext;padding: 0cm 5.4pt;vertical-align: top;">
                <p style='margin-top:0cm;margin-right:0cm;margin-bottom:0cm;margin-left:0cm;line-height:normal;font-size:15px;font-family:"Calibri",sans-serif;text-align:center;'><span style='font-size:16px;font-family:"Open Sans",sans-serif;'>0.7818</span></p>
            </td>
        </tr>
        <tr>
            <td style="width: 134.85pt;border-right: 1pt solid windowtext;border-bottom: 1pt solid windowtext;border-left: 1pt solid windowtext;border-image: initial;border-top: none;padding: 0cm 5.4pt;vertical-align: top;">
                <p style='margin-top:0cm;margin-right:0cm;margin-bottom:0cm;margin-left:0cm;line-height:normal;font-size:15px;font-family:"Calibri",sans-serif;'><span style='font-size:16px;font-family:"Open Sans",sans-serif;'>Deep Neural Decision Forest</span></p>
            </td>
            <td style="width: 134.85pt;border-top: none;border-left: none;border-bottom: 1pt solid windowtext;border-right: 1pt solid windowtext;padding: 0cm 5.4pt;vertical-align: top;">
                <p style='margin-top:0cm;margin-right:0cm;margin-bottom:0cm;margin-left:0cm;line-height:normal;font-size:15px;font-family:"Calibri",sans-serif;text-align:center;'><span style='font-size:16px;font-family:"Open Sans",sans-serif;'>90.5866%</span></p>
            </td>
            <td style="width: 134.9pt;border-top: none;border-left: none;border-bottom: 1pt solid windowtext;border-right: 1pt solid windowtext;padding: 0cm 5.4pt;vertical-align: top;">
                <p style='margin-top:0cm;margin-right:0cm;margin-bottom:0cm;margin-left:0cm;line-height:normal;font-size:15px;font-family:"Calibri",sans-serif;text-align:center;'><span style='font-size:16px;font-family:"Open Sans",sans-serif;'>0.8001</span></p>
            </td>
            <td style="width: 134.9pt;border-top: none;border-left: none;border-bottom: 1pt solid windowtext;border-right: 1pt solid windowtext;padding: 0cm 5.4pt;vertical-align: top;">
                <p style='margin-top:0cm;margin-right:0cm;margin-bottom:0cm;margin-left:0cm;line-height:normal;font-size:15px;font-family:"Calibri",sans-serif;text-align:center;'><span style='font-size:16px;font-family:"Open Sans",sans-serif;'>0.7917</span></p>
            </td>
        </tr>
    </tbody>
</table>
