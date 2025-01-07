<template>
  <div id="app">
    <div>
      <img
        v-if="isDesktop"
        class="w-100"
        :src="desktopImageSrc"
        alt="Desktop Image"
      />
      <img v-else class="w-100" :src="mobileImageSrc" alt="Mobile Image" />
    </div>

    <div class="topStrip">
      <div class="container">
        <p :style="{ fontSize: dynamicFontSize + 'px' }">
          <span class="cb-total-discount-applied">{{ totalDiscount }}</span>
          discount
          <span class="cb-discountPercentage">{{ discountPercentage }}</span>
          applied. This code expires in:
          <span id="stopwatch">{{ countdown }}</span>
        </p>
      </div>
    </div>

    <div class="top_bar_nav">
      <div class="container">
        <div class="dis-box-logo">
          <div class="logo_wrap_dist">
            <img
              src="./assets/logo.png"
              width="175"
              alt="Logo"
            />
          </div>
          <div class="box_style_thrty">
            <div class="gImg">
              <img
                src="./assets/60-day.svg"
                width="54"
                alt="60 Days Guarantee"
              />
            </div>
            <div class="mobHeader">
              <p>
                <span>
                  <img
                    src="https://offer.buycyberheater.com/offer/1/app/desktop/images/checkout-now-v4/fast-shipping.svg"
                    width="51"
                    alt="Fast Shipping"
                  />
                </span>
                Fast Shipping
              </p>
              <p>
                <span>
                  <img
                    src="https://offer.buycyberheater.com/offer/1/app/desktop/images/checkout-now-v4/call.svg"
                    width="51"
                    class="call"
                    alt="Call Icon"
                  />
                </span>
                +1 (888) 603-1954
              </p>
            </div>
            <h3 class="thrty_logos">
              <span>
                <img
                  src="./assets/fast-shipping-blue.svg"
                  width="51"
                  alt="Fast Shipping"
                />
              </span>
              <span>Fast Shipping</span>
            </h3>
            <h3 class="thrty_logos">
              <span>
                <img
                  src="./assets/60-day.svg"
                  width="54"
                  alt="60 Days Guarantee"
                />
              </span>
              <span>30-Days Money Back Guarantee</span>
            </h3>
          </div>
        </div>
      </div>
    </div>

    <div class="chk-header">
      <div class="container">
        <img
          src="./assets/mob-header.png"
          alt=""
          class="img-fluid d-md-none d-block m-auto"
        />
        <ul class="stepsBox">
          <li>
            Checkout<span
              ><img
                src="./assets/desktop-active-arrow.svg"
                alt=""
            /></span>
          </li>
          <li>
            Bonus Deals<span
              ><img
                src="./assets/desktop-active-arrow.svg"
                alt=""
            /></span>
          </li>
          <li>Receipt</li>
        </ul>
      </div>
    </div>

    <div class="checkout-section">
      <div class="container">
        <p class="chk-rgt-text1 d-none">New &amp; Improved 2026 Model</p>
        <p class="prod-name d-none">Cyber Heater</p>
        <p class="str-rvw d-none">
          <img
            src="./assets/star02.png"
            alt="Star"
          />12,421 Verified Customer Reviews
        </p>
        <div class="left-sec">
          <div
            id="sticky-sticky-wrapper"
            class="sticky-wrapper"
            style="height: 500px"
          >
            <div
              id="sticky-sticky-wrapper"
              class="sticky-wrapper"
              style="height: 500px"
            >
              <div
                id="sticky-sticky-wrapper"
                class="sticky-wrapper"
                style="height: 500px"
              >
                <div
                  id="sticky-sticky-wrapper"
                  class="sticky-wrapper"
                  style="height: 500px"
                >
                  <div
                    id="sticky-sticky-wrapper"
                    class="sticky-wrapper"
                    style="height: 500px"
                  >
                    <div
                      id="sticky-sticky-wrapper"
                      class="sticky-wrapper"
                      style="height: 610px"
                    >
                      <div
                        id="sticky-sticky-wrapper"
                        class="sticky-wrapper"
                        style="height: 610px"
                      >
                        <div
                          id="sticky-sticky-wrapper"
                          class="sticky-wrapper"
                          style="height: 610px"
                        >
                          <div
                            id="sticky-sticky-wrapper"
                            class="sticky-wrapper"
                            style="height: 610px"
                          >
                            <div
                              id="sticky-sticky-wrapper"
                              class="sticky-wrapper"
                              style="height: 610px"
                            >
                              <div
                                id="sticky-sticky-wrapper"
                                class="sticky-wrapper"
                                style="height: 610px"
                              >
                                <div
                                  id="sticky-sticky-wrapper"
                                  class="sticky-wrapper"
                                  style="height: 500px"
                                >
                                  <div
                                    id="sticky-sticky-wrapper"
                                    class="sticky-wrapper"
                                    style="height: 500px"
                                  >
                                    <div
                                      id="sticky-sticky-wrapper"
                                      class="sticky-wrapper"
                                      style="height: 500px"
                                    >
                                      <div
                                        id="sticky-sticky-wrapper"
                                        class="sticky-wrapper"
                                        style="height: 500px"
                                      >
                                        <div
                                          id="sticky-sticky-wrapper"
                                          class="sticky-wrapper"
                                          style="height: 500px"
                                        >
                                          <div
                                            id="sticky-sticky-wrapper"
                                            class="sticky-wrapper"
                                            style="height: 500px"
                                          >
                                            <div
                                              id="sticky-sticky-wrapper"
                                              class="sticky-wrapper"
                                              style="height: 500px"
                                            >
                                              <div
                                                id="sticky-sticky-wrapper"
                                                class="sticky-wrapper"
                                                style="height: 500px"
                                              >
                                                <div
                                                  id="sticky-sticky-wrapper"
                                                  class="sticky-wrapper"
                                                  style="height: 500px"
                                                >
                                                  <div
                                                    id="sticky"
                                                  >
                                                    <div
                                                      class="vehicle-detail-banner banner-content clearfix"
                                                    >
                                                      <div
                                                        class="banner-slider"
                                                      >
                                                        <div
                                                          class="slider-banner-image"
                                                        >
                                                          <img
                                                            src="./assets/black-trans2.png"
                                                            class="prd-nav"
                                                            alt="img"
                                                          />
                                                        </div>
                                                      </div>
                                                    </div>
                                                    <div class="hide-mob">
                                                      <ul class="s1-list">
                                                        <li>
                                                          <img
                                                            src="./assets/s2-apps1.png"
                                                            class="s1-ic"
                                                          />
                                                          <p>Built In Timer</p>
                                                        </li>
                                                        <li>
                                                          <img
                                                            src="./assets/s2-apps2.png"
                                                            class="s1-ic"
                                                          />
                                                          <p>Fast Heating</p>
                                                        </li>
                                                        <li>
                                                          <img
                                                            src="./assets/s2-apps3.png"
                                                            class="s1-ic"
                                                          />
                                                          <p>
                                                            Saves Your <br />
                                                            Money
                                                          </p>
                                                        </li>
                                                        <li>
                                                          <img
                                                            src="./assets/s2-apps4.png"
                                                            class="s1-ic"
                                                          />
                                                          <p>
                                                            Silent <br />
                                                            Operations
                                                          </p>
                                                        </li>
                                                      </ul>
                                                    </div>
                                                  </div>
                                                </div>
                                              </div>
                                            </div>
                                          </div>
                                        </div>
                                      </div>
                                    </div>
                                  </div>
                                </div>
                              </div>
                            </div>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="right-sec">
          <p class="chk-rgt-text1 hide-mob">New &amp; Improved 2026 Model</p>
          <p class="prod-name hide-mob">Cyber Heater</p>
          <p class="str-rvw hide-mob">
            <img
              src="./assets/star02.png"
              alt="Star"
            />12,421 Verified Customer Reviews
          </p>

          <p class="prd-det-disc">
            Cyber Heater: Instant Warmth, Ultimate Comfort.
          </p>

          <div class="q-box">
            <div class="qiconbox">
              <img
                src="./assets/q-icon.svg"
                alt="Quantity"
              />
            </div>
            <div class="qcontentbox">
              <h3>Select Quantity</h3>
              <p>Choose your package below</p>
            </div>
          </div>
          <p class="disc-hdng">
            <span
              ><img
                src="./assets/check-b.svg"
                alt="Check" /></span
            >Your <span class="cb-total-discount-applied">50%</span> Discount
            <span class="cb-discount-off" style="display: none"></span> Has Been
            Applied
          </p>
          <div class="pkg-opt">
    <div
      v-for="(product, index) in products"
      :key="index"
      class="buyopt packageClass cb-package-container"
      :id="product.id"
      :class="{ selected: selectedProduct === product.unitPrice }"
      @click="selectProduct(product.unitPrice , product.regPrice , product.id)"
    >
      <!-- <label :for="'radio-' + product.unitPrice">
      </label> -->
      <div class="buy-opt-left">
          <!-- <input
        type="radio"
        :id="'radio-' + product.unitPrice"
        :value="product.unitPrice"
        v-model="selectedProduct"
        class="product-radio"
      /> -->
          <div class="disc-product">
            <img :src="product.image" :alt="product.name" />
          </div>
          <p>
            <span class="prod-no">{{ product.quantityLabel }}</span>
          </p>
        </div>
        <div class="disc-amount">
          {{ product.discount }} % OFF
        </div>
        <div class="buy-opt-rgt">
          <p class="pkg-prc">
            <span class="cb-reg-price">${{ product.regPrice }}</span>
            <br />
            <span class="cb-buy-each font-weight-bold">${{ product.unitPrice }}</span>
            <br />
            <span class="cb-reg2">each</span>
          </p>
        </div>
    </div>
  </div>
          <div class="q-box">
            <div class="qiconbox">
              <img
                src="./assets/card.svg"
                alt="Quantity"
              />
            </div>
            <div class="qcontentbox">
              <h3>Payment Method</h3>
              <p>256-Bit Encrypted Checkout</p>
            </div>
          </div>
          <form
            class="form"
            method="post"
            action="ajax.php?method=downsell1"
            name="downsell_form1"
            accept-charset="utf-8"
            enctype="application/x-www-form-urlencoded;charset=utf-8"
            novalidate="novalidate"
          >
            <p class="disc-hdng" style="background: #ffebe3">
              <span
                ><img
                  src=".assets/alert.svg"
                  S
                  alt="Check" /></span
              >High Demand: <strong>12 People</strong> Have This in Their Cart
            </p>
            <div class="paypal-container">
              <div class="paypal-hdng">Express Checkout</div>
              <input
                type="submit"
                name="cctype"
                id="paypal_method"
                class="cb-paypemt-radio paypemt_radio cb-paypal-method"
                data-paymentmethod="paypal"
              />
              <label for="paypal_method" class="clearfix pulse"
                ><span
                  ><img
                    src="./assets/paypal-01.png" /></span
              ></label>
            </div>
            <input type="hidden" name="prospectId" id="prospectId" value="" />
            <input
              type="hidden"
              name="campaigns[1][id]"
              id="campaign_id"
              value="17"
            />
            <input
              type="hidden"
              name="campaigns[2][id]"
              id="split_click_bump"
              class="cb-split-click-bump"
              value="41"
              disabled=""
            />
            <input
              type="hidden"
              name="campaigns[2][price]"
              value="9.95"
              id="clickbumpPrice"
              class="cb-click-bump-price"
              disabled=""
            />
            <input
              type="hidden"
              name="campaigns[3][id]"
              id="split_click_bump2"
              class="cb-split-click-bump-2"
              value="49"
            />
            <input
              type="hidden"
              name="campaigns[5][id]"
              id="split_click_bump2"
              class="cb-split-click-bump-5"
              value="201"
            />
            <input
              type="hidden"
              id="dynamic-shipping-charge"
              name="dynamic_shipping_charge"
              value="14.95"
            />
            <input
              type="hidden"
              name="custom[shipping_charge]"
              value="14.95"
              id="custom-shipping-charge"
            />
            <input type="hidden" name="coupon_code" value="No Discount" />
            <input type="hidden" name="regprice" id="regprice" value="269.74" />
            <input
              type="hidden"
              name="individualPrice"
              id="individualPrice"
              value="44.96"
            />
            <input
              type="hidden"
              name="packageQuantity"
              id="packageQuantity"
              value="3"
            />
            <div class="formBox">
              <div class="clearall"></div>
              <div class="payment-flds-box">
                <p class="pkg-hdng">Shipping details</p>
                <div class="frm-flds fl form-floating">
                  <input
                    type="email"
                    name="email"
                    id="email"
                    class="input-flds required cb-remove-class frmField"
                    placeholder=""
                    data-validate="email"
                    data-error-message="Please enter a valid email id!"
                  />
                  <label for="email" class="fl-label">Email</label>
                </div>
                <div class="frm-flds fl form-floating">
                  <input
                    type="tel"
                    name="phone"
                    id="phone"
                    class="input-flds required cb-remove-class frmField form-control"
                    placeholder=""
                    data-validate="phone"
                    data-min-length="11"
                    data-max-length="17"
                    maxlength="17"
                    onkeyup="javascript:this.value=this.value.replace(/[^0-9]/g,'');"
                    data-error-message="Please enter a valid contact number!"
                    onkeypress="return isNumberKey(event)"
                  />
                  <label for="phone" class="fl-label">Phone Number</label>
                </div>
                <div class="frm-flds fl form-floating">
                  <input
                    type="text"
                    name="firstName"
                    id="firstName"
                    class="input-flds required cb-remove-class frmField"
                    placeholder=""
                    data-error-message="Please enter your first name!"
                  />
                  <label for="fname" class="fl-label">First Name</label>
                </div>
                <div class="frm-flds fl form-floating">
                  <input
                    type="text"
                    name="lastName"
                    id="lastName"
                    class="input-flds required cb-remove-class frmField"
                    placeholder=""
                    data-error-message="Please enter your last name!"
                  />
                  <label for="lanme" class="fl-label">Last Name</label>
                </div>
                <div class="frm-flds fl form-floating">
                  <select
                    name="shippingCountry"
                    type="text"
                    placeholder="Your State"
                    class="selcet-fld required cb-remove-class frmField form-select no-error"
                    data-selected="US"
                    data-error-message="Please select your country!"
                  >
                    <option value="">Select Country</option>
                    <option value="CA">Canada</option>
                    <option value="US">United States</option>
                  </select>
                  <label for="shippingCountry" class="fl-label"
                    >Select Country</label
                  >
                </div>
                <div class="frm-flds fl form-floating">
                  <input
                    type="text"
                    name="shippingAddress1"
                    class="input-flds required cb-remove-class frmField pac-target-input"
                    placeholder=""
                    data-error-message="Please enter your address!"
                    id="shipAddress"
                    autocomplete="off"
                  />
                  <label for="address" class="fl-label">Shipping Address</label>
                </div>
                <div class="frm-flds fl form-floating">
                  <input
                    type="text"
                    name="shippingCity"
                    class="input-flds required cb-remove-class frmField form-control"
                    placeholder=""
                    data-error-message="Please enter your city!"
                  />
                  <label for="city" class="fl-label">Your City</label>
                </div>
                <div class="frm-flds fl form-floating">
                  <select
                    name="shippingState"
                    type="text"
                    placeholder="Your State"
                    class="selcet-fld required cb-remove-class frmField form-select"
                    data-error-message="Please select your state!"
                    readonly="readonly"
                    data-selected=""
                  >
                    <option value="" selected="selected">Select State</option>
                    <option value="AL">Alabama</option>
                    <option value="AK">Alaska</option>
                    <option value="AS">American Samoa</option>
                    <option value="AZ">Arizona</option>
                    <option value="AR">Arkansas</option>
                    <option value="CA">California</option>
                    <option value="CO">Colorado</option>
                    <option value="CT">Connecticut</option>
                    <option value="DE">Delaware</option>
                    <option value="DC">District of Columbia</option>
                    <option value="FM">Federated States of Micronesia</option>
                    <option value="FL">Florida</option>
                    <option value="GA">Georgia</option>
                    <option value="GU">Guam</option>
                    <option value="HI">Hawaii</option>
                    <option value="ID">Idaho</option>
                    <option value="IL">Illinois</option>
                    <option value="IN">Indiana</option>
                    <option value="IA">Iowa</option>
                    <option value="KS">Kansas</option>
                    <option value="KY">Kentucky</option>
                    <option value="LA">Louisiana</option>
                    <option value="ME">Maine</option>
                    <option value="MD">Maryland</option>
                    <option value="MA">Massachusetts</option>
                    <option value="MI">Michigan</option>
                    <option value="MN">Minnesota</option>
                    <option value="MS">Mississippi</option>
                    <option value="MO">Missouri</option>
                    <option value="MT">Montana</option>
                    <option value="NE">Nebraska</option>
                    <option value="NV">Nevada</option>
                    <option value="NH">New Hampshire</option>
                    <option value="NJ">New Jersey</option>
                    <option value="NM">New Mexico</option>
                    <option value="NY">New York</option>
                    <option value="NC">North Carolina</option>
                    <option value="ND">North Dakota</option>
                    <option value="MP">Northern Mariana Islands</option>
                    <option value="OH">Ohio</option>
                    <option value="OK">Oklahoma</option>
                    <option value="OR">Oregon</option>
                    <option value="PA">Pennsylvania</option>
                    <option value="PR">Puerto Rico</option>
                    <option value="MH">Republic of Marshall Islands</option>
                    <option value="RI">Rhode Island</option>
                    <option value="SC">South Carolina</option>
                    <option value="SD">South Dakota</option>
                    <option value="TN">Tennessee</option>
                    <option value="TX">Texas</option>
                    <option value="UT">Utah</option>
                    <option value="VT">Vermont</option>
                    <option value="VI">Virgin Islands of the U.S.</option>
                    <option value="VA">Virginia</option>
                    <option value="WA">Washington</option>
                    <option value="WV">West Virginia</option>
                    <option value="WI">Wisconsin</option>
                    <option value="WY">Wyoming</option>
                  </select>
                  <label for="state" class="fl-label">State:</label>
                </div>
                <div class="frm-flds fl form-floating">
                  <input
                    type="tel"
                    name="shippingZip"
                    id="zip"
                    class="input-flds required cb-remove-class frmField form-control"
                    placeholder=""
                    data-error-message="Please enter a valid zip code!"
                  />
                  <label for="zip" class="fl-label">Zip Code:</label>
                </div>
              </div>
            </div>

            <div class="clearall"></div>
            <div class="js_choose_billing">
              <div class="w_radio">
                <input
                  type="radio"
                  id="radio_same_as_shipping"
                  name="billingSameAsShipping"
                  value="yes"
                  checked="checked"
                   @click="billingCheck()"
                />
                <label for="radio_same_as_shipping">
                  Billing is the same as shipping{{JSON.stringify(billing)}}
                </label>
                <i class="icon-check"></i>
              </div>
              <div class="w_radio">
                <input
                  type="radio"
                  id="radio_different_shipping"
                  name="billingSameAsShipping"
                  value="no"
                  @click="billingCheck()"
                />
                <label for="radio_different_shipping">
                  Billing Address different as Shipping 
                </label>
                <i class="icon-check"></i>
              </div>
            </div>
            <label class="fieldToggle" id="fieldToggle">
              <input
                type="checkbox"
                id="togData"
                class="cb-address-differs-check"
                name="billShipSame"
                 @click="billingCheck()"
              />
              <span class="togship"></span>
              Billing is the same as shipping
            </label>
            <div class="clearall"></div>
            <div v-if="billing" class="shipaddress">
              <div class="frm-flds fl form-floating">
                <input
                  type="text"
                  name="billingFirstName"
                  class="input-flds cb-remove-class-billing form-control-custom frmField form-control"
                  placeholder=""
                  data-error-message="Please enter your billing first name!"
                />
                <label for="fname" class="fl-label">Billing First Name</label>
              </div>
              <div class="frm-flds fl form-floating">
                <input
                  type="text"
                  name="billingLastName"
                  class="input-flds cb-remove-class-billing frmField form-control"
                  placeholder=""
                  data-error-message="Please enter your billing last name!"
                />
                <label for="lanme" class="fl-label">Billing Last Name</label>
              </div>
              <div class="frm-flds fl form-floating">
                <input
                  type="text"
                  name="billingAddress1"
                  class="input-flds cb-remove-class-billing frmField form-control"
                  placeholder=""
                  data-error-message="Please enter your billing address!"
                />
                <label for="address" class="fl-label">Billing Address</label>
              </div>
              <div class="frm-flds fl form-floating">
                <input
                  type="text"
                  name="billingAddress2"
                  class="input-flds form-control"
                  placeholder=""
                  id="appt"
                />
                <label for="appt" class="fl-label"
                  >Apartment, suite, etc. (optional)</label
                >
              </div>
              <div class="frm-flds fl form-floating">
                <input
                  type="text"
                  name="billingCity"
                  class="input-flds cb-remove-class-billing frmField form-control"
                  placeholder=""
                  data-error-message="Please enter your billing city!"
                />
                <label for="city" class="fl-label">Your City</label>
              </div>
              <div class="frm-flds fl form-floating">
                  <select
                    name="shippingCountry"
                    type="text"
                    placeholder="Your State"
                    class="selcet-fld required cb-remove-class frmField form-select no-error"
                    data-selected="US"
                    data-error-message="Please select your country!"
                  >
                    <option value="">Select Country</option>
                    <option value="CA">Canada</option>
                    <option value="US">United States</option>
                  </select>
                  <label for="shippingCountry" class="fl-label"
                    >Select Country</label
                  >
                </div>
              <div class="frm-flds fl form-floating">
                  <select
                    name="shippingState"
                    type="text"
                    placeholder="Your State"
                    class="selcet-fld required cb-remove-class frmField form-select"
                    data-error-message="Please select your state!"
                    readonly="readonly"
                    data-selected=""
                  >
                    <option value="" selected="selected">Select State</option>
                    <option value="AL">Alabama</option>
                    <option value="AK">Alaska</option>
                    <option value="AS">American Samoa</option>
                    <option value="AZ">Arizona</option>
                    <option value="AR">Arkansas</option>
                    <option value="CA">California</option>
                    <option value="CO">Colorado</option>
                    <option value="CT">Connecticut</option>
                    <option value="DE">Delaware</option>
                    <option value="DC">District of Columbia</option>
                    <option value="FM">Federated States of Micronesia</option>
                    <option value="FL">Florida</option>
                    <option value="GA">Georgia</option>
                    <option value="GU">Guam</option>
                    <option value="HI">Hawaii</option>
                    <option value="ID">Idaho</option>
                    <option value="IL">Illinois</option>
                    <option value="IN">Indiana</option>
                    <option value="IA">Iowa</option>
                    <option value="KS">Kansas</option>
                    <option value="KY">Kentucky</option>
                    <option value="LA">Louisiana</option>
                    <option value="ME">Maine</option>
                    <option value="MD">Maryland</option>
                    <option value="MA">Massachusetts</option>
                    <option value="MI">Michigan</option>
                    <option value="MN">Minnesota</option>
                    <option value="MS">Mississippi</option>
                    <option value="MO">Missouri</option>
                    <option value="MT">Montana</option>
                    <option value="NE">Nebraska</option>
                    <option value="NV">Nevada</option>
                    <option value="NH">New Hampshire</option>
                    <option value="NJ">New Jersey</option>
                    <option value="NM">New Mexico</option>
                    <option value="NY">New York</option>
                    <option value="NC">North Carolina</option>
                    <option value="ND">North Dakota</option>
                    <option value="MP">Northern Mariana Islands</option>
                    <option value="OH">Ohio</option>
                    <option value="OK">Oklahoma</option>
                    <option value="OR">Oregon</option>
                    <option value="PA">Pennsylvania</option>
                    <option value="PR">Puerto Rico</option>
                    <option value="MH">Republic of Marshall Islands</option>
                    <option value="RI">Rhode Island</option>
                    <option value="SC">South Carolina</option>
                    <option value="SD">South Dakota</option>
                    <option value="TN">Tennessee</option>
                    <option value="TX">Texas</option>
                    <option value="UT">Utah</option>
                    <option value="VT">Vermont</option>
                    <option value="VI">Virgin Islands of the U.S.</option>
                    <option value="VA">Virginia</option>
                    <option value="WA">Washington</option>
                    <option value="WV">West Virginia</option>
                    <option value="WI">Wisconsin</option>
                    <option value="WY">Wyoming</option>
                  </select>
                  <label for="state" class="fl-label">State:</label>
                </div>
              <div class="frm-flds fl form-floating">
                <input
                  type="tel"
                  name="billingZip"
                  class="input-flds cb-remove-class-billing frmField form-control"
                  placeholder=""
                  data-error-message="Please enter a valid billing zip code!"
                />
                <label for="zip" class="fl-label">Zip Code</label>
              </div>
            </div>

            <p class="pkg-hdng">Payment</p>
            <p>&nbsp;</p>

            <select
              name="creditCardType"
              class="form-control has-error"
              data-error-message="Please select valid card type!"
            >
              <option value="">Card Type</option>
              <option value="master">Master Card</option>
              <option value="visa">Visa</option>
              <option value="amex">Amex</option>
              <option value="discover">Discover</option>
              <option value="paypal">Paypal</option>
            </select>
            <div class="payoptbox">
              <div class="payment-cards-box cardPayOpt">
                <label class="paymybtn">
                  <input
                    type="radio"
                    class="ccard cb-paypemt-radio"
                    name="cctype"
                    value="cc"
                    checked=""
                    data-paymentmethod="credit_card"
                  />
                  Credit card
                  <img
                    src="./assets/visa-mstr-disc.png"
                    class="visa-imgg"
                  />
                </label>
              </div>
              <div class="payment-flds-box credit-card">
                <div class="frm-flds fl fl-form form-floating">
                  <input
                    type="tel"
                    name="creditCardNumber"
                    class="input-flds required frmField numeric remove"
                    maxlength="16"
                    placeholder=""
                    data-error-message="Please enter your card number!"
                    onkeyup="javascript: this.value = this.value.replace(/[^0-9]/g, '');"
                  />
                  <label for="cardNumber" class="fl-label">Card Number #</label>
                </div>
                <div class="frm-flds half-fld fl-form form-floating">
                  <input
                    type="text"
                    class="input-flds fl-input required frmField numeric remove"
                    name="expirationDate"
                    id="expirationDate"
                    placeholder=""
                    data-error-message=""
                    maxlength="7"
                    autocomplete="cc-exp"
                  />
                  <label for="expirationDate" class="fl-label">MM / YY</label>
                </div>
                <div class="frm-flds fl half-fld billing-cvv form-floating">
                  <input
                    type="tel"
                    name="CVV"
                    class="input-flds fl-input required frmField remove"
                    placeholder=""
                    id="cvv"
                    data-validate="cvv"
                    maxlength="3"
                    data-error-message="Please enter a valid CVV code!"
                  />
                  <label for="cvv" class="fl-label">CVV</label>
                </div>
                <div class="frm-flds half-fld fl-form form-floating m-0 p-0">
                  <!--<label for="month" class="fl-label">Month</label>-->
                  <select
                    name="expmonth"
                    class="selcet-fld required frmField month_exp remove"
                    data-error-message="Please select a valid expiration month!"
                    style="display: none"
                  >
                    <option value="">Month</option>
                    <option value="01">(01) January</option>
                    <option value="02">(02) February</option>
                    <option value="03">(03) March</option>
                    <option value="04">(04) April</option>
                    <option value="05">(05) May</option>
                    <option value="06">(06) June</option>
                    <option value="07">(07) July</option>
                    <option value="08">(08) August</option>
                    <option value="09">(09) September</option>
                    <option value="10">(10) October</option>
                    <option value="11">(11) November</option>
                    <option value="12">(12) December</option>
                  </select>
                </div>
                <div class="frm-flds half-fld fr m-0 p-0">
                  <!-- <label for="year" class="fl-label">Year</label>-->
                  <select
                    name="expyear"
                    class="selcet-fld required frmField month_year remove"
                    data-error-message="Please select a valid expiration year!"
                    style="display: none"
                  >
                    <option value="">Year</option>
                    <option value="25">2025</option>
                    <option value="26">2026</option>
                    <option value="27">2027</option>
                    <option value="28">2028</option>
                    <option value="29">2029</option>
                    <option value="30">2030</option>
                    <option value="31">2031</option>
                    <option value="32">2032</option>
                    <option value="33">2033</option>
                    <option value="34">2034</option>
                    <option value="35">2035</option>
                    <option value="36">2036</option>
                    <option value="37">2037</option>
                    <option value="38">2038</option>
                    <option value="39">2039</option>
                    <option value="40">2040</option>
                    <option value="41">2041</option>
                    <option value="42">2042</option>
                    <option value="43">2043</option>
                    <option value="44">2044</option>
                  </select>
                </div>

                <div class="clearall"></div>
              </div>
            </div>
            <div class="contentbox">
              <h3>Recommended Upgrades</h3>
              <p>Available Only On This Page</p>
            </div>
            <span class="disc-hdng1"
              ><span
                ><img
                  src="./assets/check-b.svg"
                  alt="Check" /></span
              >Select All Three</span
            >

            <div class="selectr-grpBox warrantyClass" id="wrnty">
              <div class="pckt_rts">
                <label class="pckt_rts_container">
                  <input
                    type="checkbox"
                    class="wrnt cb-check-status"
                    name="packopt"
                    id="checkStatus"
                    value="1"
                    data-price="9.95"
                  />
                  <span class="checkmark"></span>
                  <p class="grp-bx-text1">Cyber Heater Coverage (3-years)</p>
                </label>
                <p class="grp-bx-text2">
                  <span id="protection" class="cb-warranty-price">$9.95</span>
                </p>
              </div>
              <ul class="grpbx-list">
                <li>Accidental damage protection</li>
                <li>Free parts replacement guarantee</li>
                <li>
                  Express replacement service - we'll ship you a replacement, so
                  you don't have to wait for a repair
                </li>
                <li>24/7 priority access to Cyber Heater experts</li>
              </ul>
            </div>

            <div
              id="id9bie"
              class="bump-div-class formBox selectr-grpBox"
            >
              <!-- <h5
                id="bumpHeadingClass-3"
                class="fk-product bump-heading-class fk-element-container"
              > -->
                <label class="pckt_rts_container">
                  <input
                    type="checkbox"
                    class="wrnt cb-check-status"
                    name="packopt"
                    id="checkStatus"
                    value="1"
                    data-price="9.95"
                  />
                  <span class="checkmark"></span>
                  <p class="grp-bx-text1">YES! I Want to UPGRADE to Get Remotes!</p>
                </label>
              <section
                id="orderBumpVariants-3"
                class="orderBumpVariants-1-select section-style fk-product-section fk-product-variant1 product-section-border fk-display-flex flex-column"
              >
                <div
                  align="left"
                  class="form-group-div fk-display-flex flex-column fk-element-container mb-3 align-items-start"
                ></div>
              </section>
              <p id="orderBumpParagraph-3" class="order-bump-paragraph">
                <span
                  id="orderBumpHref-3"
                  align="center"
                  class="order-bump-href"
                >
                  ONE TIME OFFER:
                </span>

                <span id="orderBumpSpan-3">
                  Grab the Remote Upgrade for each one of my units for just
                  $9.97!
                </span>
              </p>
            </div>

            <div class="py-2 d-inline-block w-100 selectr-grpBox">
              <div class="row align-items-center">
                <div class="col-9">
                  <h3 class="nw-txt">Journey Package Protection</h3>
                </div>
                <div class="col-3">
                  <!-- <label class="switch">
                    <input
                      type="checkbox"
                      class="cb-check-status-2"
                      checked=""
                    />
                    <span class="slider round"></span>
                  </label> -->
                  <label class="switch">
        <input type="checkbox" v-model="isToggled" />
        <span class="slider"></span>
      </label>

                </div>
                <div class="clearfix"></div>
              </div>
              <div class="row">
                <div class="col-12">
                  <p class="np-txt">
                    Protection From Damage, Loss &amp; Theft For Just $3.50.
                  </p>
                </div>
              </div>
            </div>
            <div class="order-summary-section">
              <div class="orderSec">
                <p>Order Summary</p>
                <div class="item-detail-section">
                  <div class="item-detail-row mt-3">
                    <div
                      class="d-flex justify-content-between align-items-center prodImg"
                    >
                      <div class="prodSec">
                        <img
                          src="./assets/order-img.png"
                          class="img-fluid"
                        />
                        <span class="cb-package-qty">{{ selectedItems }}</span>
                      </div>
                      <p>Cyber Heater</p>
                    </div>
                    <div class="prodPrice">
                      <p class="crossPrice cb-product-original-price">
                        ${{ selectedItemValue }}
                      </p>
                      <p class="cb-product-price">${{ selectedProduct }}</p>
                    </div>
                  </div>
                  <div
                    class="item-detail-row cb-click-bump-order-sum-div d-none"
                  >
                    <div class="item-name">
                      <p class="main_prd">Cyber Heater Coverage</p>
                    </div>
                    <div class="item-price">
                      <p class="main_prd_price cb-warranty-price">$9.95</p>
                    </div>
                  </div>

                  <div
                    class="justify-content-between order-summary-item pt-2 pb-1 order-summary-template cb-click-bump-order-sum-div-5 d-flex"
                  >
                    <div>
                      <span class="cb-clickbump-product-5"
                        >Heater Remote Upgrade</span
                      >
                    </div>
                    <div>
                      <!--span class="cb-clickbump-price-3"-->
                      <span class="cb-clickbump-price-5">$9.97</span>
                    </div>
                  </div>
                  <div
                    class="item-detail-row cb-click-bump-order-sum-div-2 d-flex"
                    id="Kinetic_Pro_Fitness_Club"
                  >
                    <div class="item-name">
                      <p>Cyber Heater Journey Package Protection</p>
                    </div>
                    <div class="item-price">
                      <p><span class="cb-clickbump-price-2">$3.50</span></p>
                    </div>
                  </div>
                  <!--row-->
                  <div class="item-detail-row">
                    <div class="item-name">
                      <p class="main_prd">Subtotal</p>
                    </div>
                    <div class="item-price">
                      <p class="main_prd_price">
                        <span class="cb-gtotal-without-shipping">${{ selectedProduct + 9.97 + 3.50 }}</span>
                      </p>
                    </div>
                  </div>
                  <!--row-->
                  <div class="bdr-line"></div>

                  <div class="item-detail-row">
                    <div class="item-name">
                      <p class="main_prd">Total savings</p>
                    </div>
                    <div class="item-price">
                      <p class="main_prd_price green-bold">
                        - $<span class="cb-total-discount green-bold"
                          >{{ selectedItemValue - (selectedProduct + 9.97 + 3.50 ) }}</span
                        >
                      </p>
                    </div>
                  </div>

                  <div class="item-detail-row">
                    <div class="item-name">
                      <p class="main_prd"><strong>Total</strong></p>
                    </div>
                    <div class="item-price">
                      <p class="main_prd_price">
                        <span
                          class="cb-gtotal-without-shipping font-weight-bold"
                          >${{ selectedProduct + 9.97 + 3.50 }}</span
                        >
                      </p>
                    </div>
                  </div>
                </div>
              </div>
              <p>Shipping and tax will be settled upon checkout confirmation</p>
              <button
                type="submit"
                class="complete-btn cb-checkout-button pulse"
              >
                Complete Secure Checkout
                <img
                  src="./assets/arrow.png"
                />
              </button>
              <div class="securechecks">
                <p><span>Guaranteed Safe &amp; Secure Checkout</span></p>
                <img
                  src="./assets/secure-checkout.png"
                  class="img-fluid d-block m-auto"
                />
              </div>
            </div>
          </form>
        </div>
        <p id="loading-indicator">Processing...</p>
      </div>
    </div>

    <div class="footer">
      <div class="container">
        <p class="ftr-txt1">
          Copyright ©2025 Cyber Heater - All rights reserved.
        </p>
        <p class="ftr-txt1">
          <a
            align="center"
            href="contact.php?preselect=1&amp;C1=1377&amp;uid=13273&amp;oid=1377&amp;affid=1279&amp;AFFID=1279&amp;utm_campaign=CPA_1279&amp;utm_source=1279&amp;sub4=us&amp;sub5=1oeeR5i082P58xZXa6JMy1cNvqvOg8sjTa"
            target="_blank"
            class="link"
            >Contact Us</a
          >
          |
          <a
            align="center"
            href="terms.php?preselect=1&amp;C1=1377&amp;uid=13273&amp;oid=1377&amp;affid=1279&amp;AFFID=1279&amp;utm_campaign=CPA_1279&amp;utm_source=1279&amp;sub4=us&amp;sub5=1oeeR5i082P58xZXa6JMy1cNvqvOg8sjTa"
            target="_blank"
            class="link"
            >Terms of Use
          </a>
          |
          <a
            align="center"
            href="privacy.php?preselect=1&amp;C1=1377&amp;uid=13273&amp;oid=1377&amp;affid=1279&amp;AFFID=1279&amp;utm_campaign=CPA_1279&amp;utm_source=1279&amp;sub4=us&amp;sub5=1oeeR5i082P58xZXa6JMy1cNvqvOg8sjTa"
            target="_blank"
            class="link"
            >Privacy Policy
          </a>
        </p>
        <center>
          <a
            href="https://www.dmca.com/Protection/Status.aspx?ID=0b693e6c-31d5-424a-8417-2bacb9b8923c&amp;refurl=https://offer.buycyberheater.com/offer/1/checkout-now-v4.php?preselect=1&amp;C1=1377&amp;uid=13273&amp;oid=1377&amp;affid=1279&amp;AFFID=1279&amp;utm_campaign=CPA_1279&amp;utm_source=1279&amp;sub4=us&amp;sub5=1oeeR5i082P58xZXa6JMy1cNvqvOg8sjTa"
            title="DMCA.com Protection Status"
            target="_blank"
            class="dmca-badge">
            <img src="./assets/dmca_protected_sml_120n.png"
              alt="DMCA.com Protection Status" /></a>
        </center>
      </div>
    </div>
  </div>

<!---- pop up ----->
  <div id="leaveFade" style="display: none;">
	<div id="leavePop1" class="leavepop_all" style="display:none">
		<div id="leaveX1" class="leaveX_all">
			<img src="./assets/xclose.png">
		</div>
		<div id="innerA1" class="innerStyling innerA_all">
			<img src="./assets/bf_cm.png" class="" alt="#">
		</div>
		<div id="innerB1" class="innerStyling innerB_all">
			<p>Save an extra 10% OFF with this free coupon!</p>
		</div>
		<div id="innerD1" class="innerStyling">Congratulations! This is a special promotion that only 5 lucky visitors get per week. You must use this coupon within the next 5 minutes or it will be given away to another customer.
		</div>
		<div id="innerE1">
			<span id="timeCount">4:32</span>
		</div>
		<div id="innerF1">
			<div id="innerFa1"> MINUTES </div>
			<div id="innerFb1"> SECONDS </div>
			<div class="clear"></div>
		</div>
		<div id="innerButton1" class="innerButton_all">
			Activate My 10% OFF Coupon! 
		</div>
	</div>
	<div id="leavePop2" class="leavepop_all"  style="display: none">
		<div id="leaveX2" class="leaveX_all">
			<img src="./assets/xclose.png">
		</div>
		<div id="innerA2" class="innerStyling innerA_all">
			WAIT! Here is our BEST &amp; FINAL OFFER! 
		</div>
		<div id="innerB2" class="innerStyling innerB_all">
			Save an <span style="text-decoration: underline; color: #c00;">EXTRA 5% OFF (15% OFF TOTAL)</span> with this FREE COUPON!
		</div>
		<div id="innerButton2" class="innerButton_all">Activate 15% OFF Coupon!</div>
	</div>
</div>

<!---- Toaster ----->
<div>
    <div v-if="showNotification" class="notification-card">
      <img :src="imageSrc" alt="Product Image" class="product-image" />
      <div class="notification-details">
        <p class="notification-text">
          <strong>{{ buyerName }}</strong> in <strong>{{ location }}</strong> purchased 
          <strong>{{ quantity }}x {{ productName }}</strong>
        </p>
        <p class="notification-time">{{ timeAgo }}</p>
      </div>
    </div>
  </div>





</template>

<script>
export default {
  data() {
    return {
      products: [
        {
          id: "1",
          quantityLabel: "Buy 1",
          price: 49.95,
          regPrice: 99.90,
          discount: 50,
          unitPrice: 49.95,
          image: "src/assets/product-1x.png",
          name: "1x Cyber Heater ProPack",
        },
        {
          id: "2",
          quantityLabel: "Buy 2",
          price: 94.91,
          regPrice: 189.82,
          discount: 50,
          unitPrice: 47.45,
          image: "src/assets/product-2x.png",
          name: "2x Cyber Heaters DuoPack",
        },
        {
          id: "3",
          quantityLabel: "Buy 3",
          price: 134.87,
          regPrice: 269.74,
          discount: 50,
          unitPrice: 44.96,
          image: "src/assets/product-3x.png",
          name: "3x Cyber Heaters Multipack",
        },
        {
          id: "4",
          quantityLabel: "Buy 4",
          price: 169.83,
          regPrice: 339.66,
          discount: 50,
          unitPrice: 42.46,
          image: "src/assets/product-4x.png",
          name: "4x Cyber Heaters Deluxe Pack",
        },
        {
          id: "5",
          quantityLabel: "Buy 5",
          price: 199.80,
          regPrice: 399.60,
          discount: 50,
          unitPrice: 39.96,
          image: "src/assets/product-5x.png",
          name: "5x Cyber Heaters Family Pack",
        },
      ],
      isToggled: false,
      showNotification: false, // Controls visibility
      buyerName: "Hannah L.",
      location: "Denver, CO",
      productName: "Cyber Heaters",
      quantity: 3,
      timeAgo: "About 40 minutes ago",
      imageSrc: "src/assets/product1a.png", // Replace with your image path
      billing : false,
      selectedItemValue : null,
      selectedItems : null,
      selectedProduct: null,
      isDesktop: window.innerWidth >= 768,
      desktopImageSrc:
        "src/assets/Black_Friday_top.png",
      mobileImageSrc:
        "src/assets/Mobile_Reconstruction_1.png",
      totalDiscount: "50%", // Static value or can be dynamic
      discountPercentage: "", // Add a value here if needed
      countdown: "01:08", // Initial countdown timer value
    };

    
  },





  
  computed: {
    dynamicFontSize() {
      return this.isDesktop ? 20 : 14;
    },
  },
  mounted() {
    window.addEventListener("resize", this.handleResize);
    this.startCountdown();
    setTimeout(() => {
      this.showNotification = true;
      console.log("Notification shown: User purchased Cyber Heaters."); // Log message when notification is shown
      
      // Hide notification after 5 seconds of being visible
      setTimeout(() => {
        this.showNotification = false;
        console.log("Notification hidden."); // Log message when notification is hidden
      }, 5000); // 5 seconds delay to hide
    }, 2000); // 2 seconds delay to show

  },

  beforeUnmount() {
    window.removeEventListener("resize", this.handleResize);
  },
  methods: {
    handleResize() {
      this.isDesktop = window.innerWidth >= 768;
    },
    startCountdown() {
      let time = 8; // Countdown duration in seconds (1 minute and 8 seconds)
      const timer = setInterval(() => {
        const minutes = Math.floor(time / 60);
        const seconds = time % 60;
        this.countdown = `${String(minutes).padStart(2, "0")}:${String(
          seconds
        ).padStart(2, "0")}`;
        if (time <= 0) {
          document.getElementById("leaveFade").style.display = "block";
          document.getElementById("leavePop1").style.display = "block";
          
          document.getElementById("innerButton1").addEventListener("click", function(){
            document.getElementById("leaveFade").style.display = "block";
            document.getElementById("leavePop1").style.display = "none";
            document.getElementById("leavePop2").style.display = "block";
          }),

          document.getElementById("innerButton2").addEventListener("click", function(){
            document.getElementById("leaveFade").style.display = "none";
            document.getElementById("leavePop1").style.display = "none";
            document.getElementById("leavePop2").style.display = "none";
          }),

          document.getElementById("leaveX1").addEventListener("click", function(){
            document.getElementById("leaveFade").style.display = "none";
            document.getElementById("leavePop1").style.display = "none";
            document.getElementById("leavePop2").style.display = "none";
          }),

          document.getElementById("leaveX2").addEventListener("click", function(){
            document.getElementById("leaveFade").style.display = "none";
            document.getElementById("leavePop1").style.display = "none";
            document.getElementById("leavePop2").style.display = "none";
          }),
          clearInterval(timer);
        }
        time--;
      }, 1000);
    },
    selectProduct(productId , itemValue, items) {
      this.selectedItemValue = itemValue;
      this.selectedItems = items,
      this.selectedProduct = productId;
    },
    billingCheck(){
      this.billing = !this.billing;
    },
  },
};

</script>
