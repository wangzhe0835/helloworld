/**
 *  Name:       Wlp.java 
 * 
 *  Purpose:     White label partner class
 *              
 *  Author:    Zhe Wang
 *             Apr 07, 2015
 *        
 */
package backoffice;

import java.math.BigDecimal;
import java.util.Comparator;
import java.util.List;

public class Wlp {

	public String wlpID;                        //	WLP ID
	public boolean active;                      //	active?
	public String company;                      //	Company name
	public String clearingCode;                 //	Clearing code
	public String contactPhoneMobile;           //  Contact mobile phone #
	public String contactPhoneWork;             //  Contact work phone
	public String countryID;                    //	country ID
	public String currencyID;                   //	Currency ID
	public String defaultFavorites;				//  Default favorites (home page of Passport)
	public String defaultLayout;                //	Default layout
	public String defaultRecentInstruments;     //	Default recent instruments
	public List<String> defaultWatchList;		//  List of instruments watched
	public BigDecimal finSpread1;               //	Financing spread Tier 1 (1:1 - 50:1)
	public BigDecimal finSpread2;               //	Financing spread Tier 2 (51:1 - 100:1)
	public BigDecimal finSpread3;               //	Financing spread Tier 3 (101:1 - 400:1)
	public List<String> instrumentBlackList;	//  List of instruments *not* offered (Future use)
	public List<String> instrumentWhiteList;	//  List of instruments offered
	public String languageID;                   //	Default language ID
	public BigDecimal marginDefault;            //	Default margin on new accounts
	public BigDecimal marginMin;                //	Min permitted margin on an account
	public int practicePeriod;                  //	Practice period in days (0=non-expiring)
	public String prefix;                       //	Prefix to use for live (and test) acct #s
	public String prefixPractice;               //  Prefix to use for practice acct #s
	public String regulatorID;                  //  Regulator ID
	public String riskOwnedByID;                //  Risk owned by ID
	public String wlpHash;                      //  Hash key for WLP
	public List<String> currencies;             //	List of currencies this WLP allows accounts to be denominated in
	public String urlLogo;                      //	Logo url for white label
	
	

	
	public String getWlpID() {
		return wlpID;
	}
	public void setWlpID(String wlpID) {
		this.wlpID = wlpID;
	}
	public boolean isActive() {
		return active;
	}
	public void setActive(boolean active) {
		this.active = active;
	}

	public String getClearingCode() {
		return clearingCode;
	}
	public void setClearingCode(String clearingCode) {
		this.clearingCode = clearingCode;
	}
	public String getCompany() {
		return company;
	}
	public void setCompany(String company) {
		this.company = company;
	}
	public String getContactPhoneMobile() {
		return contactPhoneMobile;
	}
	public void setContactPhoneMobile(String contactPhoneMobile) {
		this.contactPhoneMobile = contactPhoneMobile;
	}
	public String getContactPhoneWork() {
		return contactPhoneWork;
	}
	public void setContactPhoneWork(String contactPhoneWork) {
		this.contactPhoneWork = contactPhoneWork;
	}
	public String getCountryID() {
		return countryID;
	}
	public void setCountryID(String countryID) {
		this.countryID = countryID;
	}
	public String getCurrencyID() {
		return currencyID;
	}
	public void setCurrencyID(String currencyID) {
		this.currencyID = currencyID;
	}
	public List<String> getCurrencies() {
		return currencies;
	}
	public void setCurrencies(List<String> currencies) {
		this.currencies = currencies;
	}
	public String getDefaultFavorites() {
		return defaultFavorites;
	}
	public void setDefaultFavorites(String defaultFavorites) {
		this.defaultFavorites = defaultFavorites;
	}
	public String getDefaultLayout() {
		return defaultLayout;
	}
	public void setDefaultLayout(String defaultLayout) {
		this.defaultLayout = defaultLayout;
	}
	public String getDefaultRecentInstruments() {
		return defaultRecentInstruments;
	}
	public void setDefaultRecentInstruments(String defaultRecentInstruments) {
		this.defaultRecentInstruments = defaultRecentInstruments;
	}
	public BigDecimal getFinSpread1() {
		return finSpread1;
	}
	public void setFinSpread1(BigDecimal finSpread1) {
		this.finSpread1 = finSpread1;
	}
	public BigDecimal getFinSpread2() {
		return finSpread2;
	}
	public void setFinSpread2(BigDecimal finSpread2) {
		this.finSpread2 = finSpread2;
	}
	public BigDecimal getFinSpread3() {
		return finSpread3;
	}
	public void setFinSpread3(BigDecimal finSpread3) {
		this.finSpread3 = finSpread3;
	}
	public List<String> getInstrumentBlackList() {
		return instrumentBlackList;
	}
	public void setInstrumentBlackList(List<String> instrumentBlackList) {
		this.instrumentBlackList = instrumentBlackList;
	}
	public List<String> getDefaultWatchList() {
		return defaultWatchList;
	}
	public void setDefaultWatchList(List<String> defaultWatchList) {
		this.defaultWatchList = defaultWatchList;
	}
	public List<String> getInstrumentWhiteList() {
		return instrumentWhiteList;
	}
	public void setInstrumentWhiteList(List<String> instrumentWhiteList) {
		this.instrumentWhiteList = instrumentWhiteList;
	}
	public String getLanguageID() {
		return languageID;
	}
	public void setLanguageID(String languageID) {
		this.languageID = languageID;
	}
	public BigDecimal getMarginDefault() {
		return marginDefault;
	}
	public void setMarginDefault(BigDecimal marginDefault) {
		this.marginDefault = marginDefault;
	}
	public BigDecimal getMarginMin() {
		return marginMin;
	}
	public void setMarginMin(BigDecimal marginMin) {
		this.marginMin = marginMin;
	}
	public int getPracticePeriod() {
		return practicePeriod;
	}
	public void setPracticePeriod(int practicePeriod) {
		this.practicePeriod = practicePeriod;
	}
	public String getPrefix() {
		return prefix;
	}
	public void setPrefix(String prefix) {
		this.prefix = prefix;
	}
	public String getPrefixPractice() {
		return prefixPractice;
	}
	public void setPrefixPractice(String prefixPractice) {
		this.prefixPractice = prefixPractice;
	}
	public String getRegulatorID() {
		return regulatorID;
	}
	public void setRegulatorID(String regulatorID) {
		this.regulatorID = regulatorID;
	}
	public String getRiskOwnedByID() {
		return riskOwnedByID;
	}
	public void setRiskOwnedByID(String riskOwnedByID) {
		this.riskOwnedByID = riskOwnedByID;
	}
	public String getWlpHash() {
		return wlpHash;
	}
	public void setWlpHash(String wlpHash) {
		this.wlpHash = wlpHash;
	}
	public String getUrlLogo() {
		return urlLogo;
	}
	public void setUrlLogo(String urlLogo) {
		this.urlLogo = urlLogo;
	}

	public static Comparator<Wlp> wlpNameOrder =new Comparator<Wlp>(){
		public int compare(Wlp w1, Wlp w2) {
            return w1.getCompany().compareTo(w2.getCompany());
        }
	};


}
