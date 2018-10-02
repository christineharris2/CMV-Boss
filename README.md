<style>
    form {
  /* Just to center the form on the page */
  margin: 0 auto;
  width: 850px;
  /* To see the outline of the form */
  padding: 1em;
  border: 1px solid #CCC;
  border-radius: 1em;
}

form div + div {
  margin-top: 1em;
}

label {
  /* To make sure that all labels have the same size and are properly aligned */
  display: inline-block;
  width: 700px;
  text-align: right;
}

input, textarea {
  /* To make sure that all text fields have the same font settings
     By default, textareas have a monospace font */
  font: 1em sans-serif;

  /* To give the same size to all text fields */
  width: 150px;
  box-sizing: border-box;

  /* To harmonize the look & feel of text field border */
  border: 1px solid #999;
}

input:focus, textarea:focus {
  /* To give a little highlight on active elements */
  border-color: #000;
}

textarea {
  /* To properly align multiline text fields with their labels */
  vertical-align: top;

  /* To give enough room to type some text */
  height: 5em;
}

.button {
  /* To position the buttons to the same position of the text fields */
  padding-left: 90px; /* same size as the label elements */
}

button {
  /* This extra margin represent roughly the same space as the space
     between the labels and their text fields */
  margin-left: .5em;
}
</style>
<form action="/my-handling-form-page" method="post">  
  <div>
    <label for="name">Name:</label>
    <input type="text" id="name" name="user_name">
  </div>
  <div>
    <label for="mail">E-mail:</label>
    <input type="email" id="mail" name="user_mail">
  </div>
    <div>
    <label for="gym_name">Gym and Team Name:</label>
    <input type="text" id="gym_name">
  </div>
  <div>
    <label for="details">Team Details:</label>
    <textarea id="details"></textarea>
  </div>
  <div>
      <header></header>
<form>
<li class="form-line" data-type="control_matrix" id="id_19">
          <label class="form-label form-label-left form-label-auto" id="label_19" for="input_19"> What rap vocalz do you need for this team? ($14/8ct) </label>
          <div id="cid_19" class="form-input">
            <table summary="" cellpadding="4" cellspacing="0" class="form-matrix-table" data-component="matrix">
              <tbody>
                <tr>
                  <th style="border:none"></th>
                  <th class="form-matrix-column-headers form-matrix-column_0">
                    1/8count
                  </th>
                  <th class="form-matrix-column-headers form-matrix-column_1">
                    2/8count
                  </th>
                  <th class="form-matrix-column-headers form-matrix-column_2">
                    3/8count
                  </th>
                  <th class="form-matrix-column-headers form-matrix-column_3">
                    4/8count
                  </th>
                </tr>
                <tr>
                  <th style="text-align:left" class="form-matrix-row-headers">
                    CrimsonMuzik
                  </th>
                  <td style="text-align:center" class="form-matrix-values">
                    <input type="text" id="input_19_0_0" class="form-textbox validate[Currency]" size="5" name="q19_whatRap[0][]" style="width:100%;box-sizing:border-box" value="">
                  </td>
                  <td style="text-align:center" class="form-matrix-values">
                    <input type="text" id="input_19_0_1" class="form-textbox validate[Currency]" size="5" name="q19_whatRap[0][]" style="width:100%;box-sizing:border-box" value="">
                  </td>
                  <td style="text-align:center" class="form-matrix-values">
                    <input type="text" id="input_19_0_2" class="form-textbox validate[Currency]" size="5" name="q19_whatRap[0][]" style="width:100%;box-sizing:border-box" value="">
                  </td>
                  <td style="text-align:center" class="form-matrix-values">
                    <input type="text" id="input_19_0_3" class="form-textbox validate[Currency]" size="5" name="q19_whatRap[0][]" style="width:100%;box-sizing:border-box" value="">
                  </td>
                </tr>
                <tr>
                  <th style="text-align:left" class="form-matrix-row-headers">
                    Emrich
                  </th>
                  <td style="text-align:center" class="form-matrix-values">
                    <input type="text" id="input_19_1_0" class="form-textbox validate[Currency]" size="5" name="q19_whatRap[1][]" style="width:100%;box-sizing:border-box" value="">
                  </td>
                  <td style="text-align:center" class="form-matrix-values">
                    <input type="text" id="input_19_1_1" class="form-textbox validate[Currency]" size="5" name="q19_whatRap[1][]" style="width:100%;box-sizing:border-box" value="">
                  </td>
                  <td style="text-align:center" class="form-matrix-values">
                    <input type="text" id="input_19_1_2" class="form-textbox validate[Currency]" size="5" name="q19_whatRap[1][]" style="width:100%;box-sizing:border-box" value="">
                  </td>
                  <td style="text-align:center" class="form-matrix-values">
                    <input type="text" id="input_19_1_3" class="form-textbox validate[Currency]" size="5" name="q19_whatRap[1][]" style="width:100%;box-sizing:border-box" value="">
                  </td>
                </tr>
                <tr>
                  <th style="text-align:left" class="form-matrix-row-headers">
                    Troy
                  </th>
                  <td style="text-align:center" class="form-matrix-values">
                    <input type="text" id="input_19_2_0" class="form-textbox validate[Currency]" size="5" name="q19_whatRap[2][]" style="width:100%;box-sizing:border-box" value="">
                  </td>
                  <td style="text-align:center" class="form-matrix-values">
                    <input type="text" id="input_19_2_1" class="form-textbox validate[Currency]" size="5" name="q19_whatRap[2][]" style="width:100%;box-sizing:border-box" value="">
                  </td>
                  <td style="text-align:center" class="form-matrix-values">
                    <input type="text" id="input_19_2_2" class="form-textbox validate[Currency]" size="5" name="q19_whatRap[2][]" style="width:100%;box-sizing:border-box" value="">
                  </td>
                  <td style="text-align:center" class="form-matrix-values">
                    <input type="text" id="input_19_2_3" class="form-textbox validate[Currency]" size="5" name="q19_whatRap[2][]" style="width:100%;box-sizing:border-box" value="">
                  </td>
                </tr>
                <tr>
                  <th style="text-align:left" class="form-matrix-row-headers">
                    Cypher T
                  </th>
                  <td style="text-align:center" class="form-matrix-values">
                    <input type="text" id="input_19_3_0" class="form-textbox validate[Currency]" size="5" name="q19_whatRap[3][]" style="width:100%;box-sizing:border-box" value="">
                  </td>
                  <td style="text-align:center" class="form-matrix-values">
                    <input type="text" id="input_19_3_1" class="form-textbox validate[Currency]" size="5" name="q19_whatRap[3][]" style="width:100%;box-sizing:border-box" value="">
                  </td>
                  <td style="text-align:center" class="form-matrix-values">
                    <input type="text" id="input_19_3_2" class="form-textbox validate[Currency]" size="5" name="q19_whatRap[3][]" style="width:100%;box-sizing:border-box" value="">
                  </td>
                  <td style="text-align:center" class="form-matrix-values">
                    <input type="text" id="input_19_3_3" class="form-textbox validate[Currency]" size="5" name="q19_whatRap[3][]" style="width:100%;box-sizing:border-box" value="">
                  </td>
                </tr>
                <tr>
                  <th style="text-align:left" class="form-matrix-row-headers">
                    Angel
                  </th>
                  <td style="text-align:center" class="form-matrix-values">
                    <input type="text" id="input_19_4_0" class="form-textbox validate[Currency]" size="5" name="q19_whatRap[4][]" style="width:100%;box-sizing:border-box" value="">
                  </td>
                  <td style="text-align:center" class="form-matrix-values">
                    <input type="text" id="input_19_4_1" class="form-textbox validate[Currency]" size="5" name="q19_whatRap[4][]" style="width:100%;box-sizing:border-box" value="">
                  </td>
                  <td style="text-align:center" class="form-matrix-values">
                    <input type="text" id="input_19_4_2" class="form-textbox validate[Currency]" size="5" name="q19_whatRap[4][]" style="width:100%;box-sizing:border-box" value="">
                  </td>
                  <td style="text-align:center" class="form-matrix-values">
                    <input type="text" id="input_19_4_3" class="form-textbox validate[Currency]" size="5" name="q19_whatRap[4][]" style="width:100%;box-sizing:border-box" value="">
                  </td>
                </tr>
                <tr>
                  <th style="text-align:left" class="form-matrix-row-headers">
                    Caz Chill
                  </th>
                  <td style="text-align:center" class="form-matrix-values">
                    <input type="text" id="input_19_5_0" class="form-textbox validate[Currency]" size="5" name="q19_whatRap[5][]" style="width:100%;box-sizing:border-box" value="">
                  </td>
                  <td style="text-align:center" class="form-matrix-values">
                    <input type="text" id="input_19_5_1" class="form-textbox validate[Currency]" size="5" name="q19_whatRap[5][]" style="width:100%;box-sizing:border-box" value="">
                  </td>
                  <td style="text-align:center" class="form-matrix-values">
                    <input type="text" id="input_19_5_2" class="form-textbox validate[Currency]" size="5" name="q19_whatRap[5][]" style="width:100%;box-sizing:border-box" value="">
                  </td>
                  <td style="text-align:center" class="form-matrix-values">
                    <input type="text" id="input_19_5_3" class="form-textbox validate[Currency]" size="5" name="q19_whatRap[5][]" style="width:100%;box-sizing:border-box" value="">
                  </td>
                </tr>
                <tr>
                  <th style="text-align:left" class="form-matrix-row-headers">
                    T-Ravill
                  </th>
                  <td style="text-align:center" class="form-matrix-values">
                    <input type="text" id="input_19_6_0" class="form-textbox validate[Currency]" size="5" name="q19_whatRap[6][]" style="width:100%;box-sizing:border-box" value="">
                  </td>
                  <td style="text-align:center" class="form-matrix-values">
                    <input type="text" id="input_19_6_1" class="form-textbox validate[Currency]" size="5" name="q19_whatRap[6][]" style="width:100%;box-sizing:border-box" value="">
                  </td>
                  <td style="text-align:center" class="form-matrix-values">
                    <input type="text" id="input_19_6_2" class="form-textbox validate[Currency]" size="5" name="q19_whatRap[6][]" style="width:100%;box-sizing:border-box" value="">
                  </td>
                  <td style="text-align:center" class="form-matrix-values">
                    <input type="text" id="input_19_6_3" class="form-textbox validate[Currency]" size="5" name="q19_whatRap[6][]" style="width:100%;box-sizing:border-box" value="">
                  </td>
                </tr>
                <tr>
                  <th style="text-align:left" class="form-matrix-row-headers"><br>
                    Elokk
                    
                  </th>
                  <td style="text-align:center" class="form-matrix-values">
                    <input type="text" id="input_19_7_0" class="form-textbox validate[Currency]" size="5" name="q19_whatRap[7][]" style="width:100%;box-sizing:border-box" value="">
                  </td>
                  <td style="text-align:center" class="form-matrix-values">
                    <input type="text" id="input_19_7_1" class="form-textbox validate[Currency]" size="5" name="q19_whatRap[7][]" style="width:100%;box-sizing:border-box" value="">
                  </td>
                  <td style="text-align:center" class="form-matrix-values">
                    <input type="text" id="input_19_7_2" class="form-textbox validate[Currency]" size="5" name="q19_whatRap[7][]" style="width:100%;box-sizing:border-box" value="">
                  </td>
                  <td style="text-align:center" class="form-matrix-values">
                    <input type="text" id="input_19_7_3" class="form-textbox validate[Currency]" size="5" name="q19_whatRap[7][]" style="width:100%;box-sizing:border-box" value="">
                  </td>
                </tr>
                <tr>
                  <th style="text-align:left" class="form-matrix-row-headers">
                    Sammy Sno
                  </th>
                  <td style="text-align:center" class="form-matrix-values">
                    <input type="text" id="input_19_8_0" class="form-textbox validate[Currency]" size="5" name="q19_whatRap[8][]" style="width:100%;box-sizing:border-box" value="">
                  </td>
                  <td style="text-align:center" class="form-matrix-values">
                    <input type="text" id="input_19_8_1" class="form-textbox validate[Currency]" size="5" name="q19_whatRap[8][]" style="width:100%;box-sizing:border-box" value="">
                  </td>
                  <td style="text-align:center" class="form-matrix-values">
                    <input type="text" id="input_19_8_2" class="form-textbox validate[Currency]" size="5" name="q19_whatRap[8][]" style="width:100%;box-sizing:border-box" value="">
                  </td>
                  <td style="text-align:center" class="form-matrix-values">
                    <input type="text" id="input_19_8_3" class="form-textbox validate[Currency]" size="5" name="q19_whatRap[8][]" style="width:100%;box-sizing:border-box" value="">
                  </td>
                </tr>
              </tbody>
            </table>
          </div>
        </li>
</div>
  <div class="button">
  <button type="submit">Send your message</button>
</div>
</form>
