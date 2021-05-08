# Requirements

The idea is to have a app where you can browse nearby stores, any kind of store, and know if the item you want is in store. In times like this pandemic, a app like this will help people know which store has their item in stock.

The delivery from the store can be done using dunzo, or the customer themselves can get it from the store. Since this is a locality based app, you always get the nearest store.

---

## Phase 1

1. The Customer should be able to view the nearby stores on a map, the type of store should be indicated on the map, as well as a filter for kind of store you want to see.
2. The Customer can select a store on the map to view what all items that are in stock.
3. The Seller can publish their store on the app along with all details of the store, this is the seller onboarding process.

### Data Models


**Customer**

```
- name
- phone number
- home_address
```

**Seller**

```
- name
- phone_number
- stores
```

**Store**

```
- name
- store type (grocery/medical/electronics)
- location (lat, lng)
- items
```

**Item**

```
- name
- quantity_available
- price
```

---

## Phase 2

1. The Customer can order something from the store
2. Payment would be done using a Gateway (Razorpay/PayTM)
3. The Seller can accept/reject the order
4. The Seller can dispatch the order using Dunzo, or any other delivery service
5. The Seller can view a dashboard that shows his store's profits, and number of items sold, most popular product, basically an admin dashboard
6. A Search bar on the maps screen to search for a product

---

## Phase 3

- Yet to be Decided
